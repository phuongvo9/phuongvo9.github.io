# Fixing Git Push Error with Multiple GitHub Accounts

## Problem
When pushing to a GitHub repository, you may encounter the following error:
```bash
❯ git push origin
ERROR: Permission to <repository>.git denied to <username>.
fatal: Could not read from remote repository.
Please make sure you have the correct access rights
and the repository exists.
```

## Solution
To resolve this issue, follow these steps to configure SSH for multiple GitHub accounts.

### 1. Generate SSH Keys for Each Account
Generate a new SSH key for each GitHub account:
```bash
ssh-keygen -t ed25519 -C "your_email@example.com" -f "~/.ssh/id_ed25519_github_account1"
ssh-keygen -t ed25519 -C "your_email@example.com" -f "~/.ssh/id_ed25519_github_account2"
```

### 2. Add SSH Keys to GitHub
Copy the public key to your clipboard:
```bash
pbcopy < ~/.ssh/id_ed25519_github_account1.pub
pbcopy < ~/.ssh/id_ed25519_github_account2.pub
```
Go to GitHub, navigate to **Settings > SSH and GPG keys**, and add the new keys.

### 3. Register SSH Keys with the SSH Agent
Start the SSH agent and add your SSH keys:
```bash
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519_github_account1
ssh-add ~/.ssh/id_ed25519_github_account2
```

### 4. Create an SSH Config File
Open or create the 

config

 file in your `.ssh` directory:
```bash
nano ~/.ssh/config
```
Add the following configuration for each account:
```bash
Host github-account1
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_ed25519_github_account1

Host github-account2
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_ed25519_github_account2
```

### 5. Clone Repositories Using the Configured Hosts
When cloning a repository, use the host specified in your config file:
```bash
git clone git@github-account1:username/repo.git
git clone git@github-account2:username/repo.git
```

### 6. Fixing the Push Error
If you encounter the push error, use `ssh-add` to add the correct key:
```bash
ssh-add ~/.ssh/id_ed25519_github_account1
```
Verify the key is added:
```bash
ssh -T git@github-account1
Hi account1! You've successfully authenticated, but GitHub does not provide shell access.
```

### 7. Clear Credential Cache
Clear the Git credential cache and push again:
```bash
git credential-cache exit
git push origin
```

## Example
```bash
ssh-add ~/.ssh/id_ed25519_github_account1
Identity added: /Users/username/.ssh/id_ed25519_github_account1 (your_email@example.com)

ssh -T git@github-account1
Hi account1! You've successfully authenticated, but GitHub does not provide shell access.

git credential-cache exit
git push origin

remote: Resolving deltas: 100% (11/11), completed with 3 local objects.
To github-account1:username/repo.git
   f0bc638..3437190  branch-name -> branch-name
```
