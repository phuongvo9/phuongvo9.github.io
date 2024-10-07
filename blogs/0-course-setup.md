# Course Setup - Getting Started

Welcome to the **DevOps for Beginners** course! This document will guide you through setting up the development environment needed to get started.

## Prerequisites

To get the most out of this course, you will need the following installed on your machine:

- **Git** - for version control ([Download Git](https://git-scm.com/downloads)).
- **Visual Studio Code (VS Code)** - for writing and editing code ([Download VS Code](https://code.visualstudio.com/)).
- **Docker** - for containerization ([Download Docker](https://www.docker.com/get-started)).
- **Node.js** (optional) - for serving documentation locally ([Download Node.js](https://nodejs.org/)).

Ensure you have administrator access to install the required software.

## Step 1: Clone the Repository

First, clone the course repository to your local machine:

```bash
git clone https://github.com/phuongvo9/DevOps-Essentials
```

## Step 2: Install VS Code Extensions

We recommend the following extensions to enhance your learning experience:

1. **Docker Extension** - Manage Docker containers directly in VS Code.
2. **Markdown Preview Enhanced** - To render Markdown files for documentation.
3. **GitLens** - To make Git integration easier and more informative.

To install these extensions:

- Open VS Code
- Go to the Extensions tab (left sidebar)
- Search for the extension name and click "Install"

## Step 3: Setup Docker Environment

Make sure Docker is running on your system. Verify by running the following command:

```bash
docker --version
```

If Docker is installed correctly, this command will output the Docker version.

## Step 4: Verify Setup

Run the following commands to verify that Git, Docker, and Node.js (if used) are installed:

```bash
git --version
docker --version
node --version
```

If these commands display the respective versions, then your environment is ready!

---

For any questions or issues, please reach me via LinkedIn

## Next Step

Once your environment is set up, proceed to the next document to learn how to run the course code.

[How to Run the Code](./how-to-run.md)

# How to Run the Course Code

This document will guide you through running and testing the sample code provided throughout the course.

## Step 1: Running the Documentation Locally

You can run the documentation locally using **Docsify**. If you don't have Node.js installed, you will need to do so first. Then, install Docsify globally:

```bash
npm install -g docsify-cli
```

Once Docsify is installed, navigate to the course directory and serve the documentation:

```bash
cd devops-for-beginners
docsify serve ./
```

This will start a local server, and you can view the documentation by opening your browser at [http://localhost:3000](http://localhost:3000).

## Step 2: Running Docker Containers

Some lessons include Docker-based exercises. You can run the Docker containers as follows:

Navigate to the relevant folder for the lesson that contains a Dockerfile and run:

```bash
docker build -t lesson-container .
docker run -d -p 8080:80 lesson-container
```

This will build and start the container, mapping it to port 8080 on your local machine.

## Step 3: Run Python/Bash Scripts

Throughout the course, you will encounter **Python** or **Bash** scripts for various automation tasks.
To execute a script, navigate to the appropriate directory and use the following command:

For Python scripts:

```bash
python script_name.py
```

For Bash scripts:

```bash
bash script_name.sh
```

## Troubleshooting Tips

- Make sure all required services (e.g., Docker, Git) are running.
- If you encounter permission issues on Linux/macOS, use `sudo` for the commands.

For any questions or issues, please reach me via LinkedIn

---
