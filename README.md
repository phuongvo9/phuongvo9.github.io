# Phuong Vo's DevOps Journey

Welcome to Phuong Vo's DevOps journey! Here, I share my experiences, insights, and knowledge about DevOps and Cloud computing. Whether you're a beginner or a seasoned professional, I hope you'll find something useful and interesting.

In this site, you will find:
- **Real-world case studies** showcasing DevOps projects.
- **Tool reviews** and comparisons to help you choose the best stack.
- **Step-by-step tutorials** to build your skills in cloud computing, automation, and more.
- **Career advice** for those looking to break into the field or take their skills to the next level.
- **Interviews with industry experts**, providing insights from professionals.
- **My personal reflections** on the evolving field of DevOps.
- **DevOps for Beginners** A curriculum to learn and hands-on practice


## Navigation
- [Home](https://phuongvo9.github.io)
- [About](#introduction)
- [Contact](#contact)
- [Blog Categories](#categories)
- [Support Me on BuyMeACoffee](https://buymeacoffee.com/phuongvo)

---

## Featured Posts
Here are some of the must-read posts to get started:
- [DevOps for Beginners: A Curriculum](#devops-for-beginners---a-curriculum)

---

## Categories

### Tutorials and How-Tos
Step-by-step guides to mastering essential DevOps skills.
- **[DevOps for Beginners: A Curriculum](#devops-for-beginners---a-curriculum)**  
  A structured learning path for newcomers in DevOps, covering topics like automation, cloud services, and CI/CD pipelines.

---

### Career Advice
Tips and personal experiences on growing your DevOps career.
- **[Career Tip: Building Your DevOps Portfolio](/blogs/career-tip/building-your-devops-porfolio.md)**  
    Breaking into the DevOps field can be challenging, but with the right approach, you can build a strong portfolio that will help you land internships, fresher positions, and eventually, more advanced roles. This guide will walk you through the steps to create a compelling DevOps portfolio and provide tips for your career progression.  

- **[Advice: Certifications That Matter](/blogs/career-advice/certification-in-devops-matter-or-not.md)**  
  A breakdown of the certifications that can boost your career in DevOps.

- **[Machine learning beginner's guide](/blogs/career-advice/machine-learning-beginners-guide.md)**  
  A beginner's guide to machine learning path for beginner
---

### Problem-Solving Stories
Troubleshooting and problem-solving stories in live production or preprod environments.
- **[Understand Let's encrypt DNS SERVFAIL error](/blogs/problem-solving/2024-10-18-fix-dns-error-servfail-txt-acme-challenge.md)**  
  If you're using Let's encrypt and have error on SERVFAIL DNS-01 authentication problem
- **[Fixing 404 Errors on a Docsify Site Hosted on GitHub Pages](./blogs/problem-solving/2024-10-15-fix-404-error-docsify-github-pages.md)**  
  If you're using Docsify to host your static website on GitHub Pages, you might have encountered a frustrating issue: navigating directly to a specific page results in a "404 Page Not Found" error. This guide helps you resolve it

- **[Fixing Git Push Error with Multiple GitHub Accounts](./blogs/problem-solving/2024-12-23-Fixing-Git-Push-Error-with-Multiple-GitHub-Accounts.md)**


### Project Case Studies
Deep dives into real-world projects I've worked on, with a focus on practical challenges and solutions.

- **[Building a Scalable and Secure Media Management Solution on Azure Kubernetes Service](blogs/project-case/building-a-scalable-secure-media-management-solution-aks)**  

- **[Implementing GitOps with FluxCD on Azure Kubernetes Service (AKS)](#project-case-studies)**  
  This case study explores how we leveraged FluxCD to implement GitOps on Azure Kubernetes Service (AKS). It covers the setup process, challenges faced, and the benefits of using GitOps for continuous deployment

- **[Scaling Applications with Azure Kubernetes Service and GitOps](#project-case-studies)** 
  This case study focuses on how we used Azure Kubernetes Service (AKS) and GitOps to scale applications efficiently. It discusses the architecture, deployment strategies, and the impact on application performance and reliability.

- **[Optimizing Resource Management with Infrastructure as Code on Azure](#project-case-studies)** 
  This project highlights how we optimized resource management on Azure using Infrastructure as Code (IaC) tools like ARM templates and Terraform. It discusses the strategies for resource allocation, cost management, and the overall impact on operational efficiency.

- **[Deploying Microservices on Azure Kubernetes Service with GitOps](#project-case-studies)** 
  This case study provides a detailed guide on deploying microservices on Azure Kubernetes Service (AKS) using GitOps. It covers the architecture, deployment process, and the benefits of using GitOps for managing microservices.

- **[Troubleshooting APNs Push Notification Issue for Live Activities in iOS](blogs/project-case/Troubleshooting-APNs-Push-Notification-Issue-for-Live-Activities-in-iOS)** 


---

### Tool Reviews and Comparisons
  Reviews of popular DevOps tools, and my experiences working with them.
- **[GitOps: ArgoCD vs FluxCD](#gitops-argocd-and-fluxcd)**  
  An comparison of two GitOps solutions—when to use each, their strengths, and weaknesses.

---

## Contact
- LinkedIn: [Phuong.VoHuy](https://www.linkedin.com/in/phuongvohuy/)

---

# DevOps for Beginners - A Curriculum

|![ Sketchnote ](./assets/images/devops-overview.png)|
|:---:|
| DevOps For Beginners - _Sketchnote Overview_ |

Explore the world of **DevOps** with the 12-week, 24-lesson curriculum! It includes practical lessons, quizzes, and labs. The curriculum is beginner-friendly and covers tools like Kubernetes, Terraform, Azure, and AWS, as well as DevOps best practices and automation.

## What you will learn

**[Mindmap of the Course](./assets/mindmap-devops.html)**


In this curriculum, you will learn:

* **GitOps** principles and how to use **Git** as a single source of truth for Kubernetes environments.
* **Cloud Services** like **AWS** and **Azure**, and how to manage infrastructure across multiple cloud platforms.
* **Container Orchestration** with **Kubernetes** to automate deployment, scaling, and management of applications.
* **Infrastructure as Code (IaC)** tools such as **Terraform** and **ARM templates** for automating infrastructure deployment.
* **CI/CD** (Continuous Integration/Continuous Delivery) with **Azure Pipelines** and **Azure DevOps**.
* Shell scripting and automation using **Bash** and **Linux**.
* **Python** for automating repetitive DevOps tasks and writing infrastructure tests.

What we will not cover in this curriculum:

> [Find all additional resources for this course in our recommended collection](https://github.com/phuongvo9/DevOps-Essentials)

* **Advanced Security Practices**. Consider taking dedicated courses on **DevSecOps** for comprehensive security practices in DevOps.
* **Cloud Cost Management** techniques. This topic is well covered in specialized resources for optimizing cloud expenditures.
* **Legacy Systems Integration** with DevOps tools.
* **Deep Monitoring and Observability** beyond the basics taught here.

## Content
| No. |                                                                 Lesson Link                                                                  |                                           Tools & Frameworks                                          | Lab                                                            |
| :-: | :------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------: | ------------------------------------------------------------------------------ |
| 0  |                                 [Course Setup](./blogs/0-course-setup.md)                                 |                      [Setup Your Development Environment](./blogs/0-environment-setup.md)                       |   |
| I  |               [**Getting started with the basics**](./blogs/1-getting-started-basics.md)      | | |
| 1  |       [Introduction and History of DevOps](./blogs/1-introduction-history.md)       |           -  | [Lab](./blogs/Introduction-To-DevOps/M1-Assignment.md)  |
| 2  |       [Business case for DevOps](./blogs/2-Business-case-for-DevOps.md)       |           -                            | [Lab](./blogs/Introduction-To-DevOps/M1-Assignment.md)  |
| 2.3  |       [Embracing DevOps for Enterprise](./blogs/2.3-devops-adoption-enterprise.md)       |- | [Lab-2.3](./blogs/2.3-devops-adoption-quiz.md)  |
| 3A  |       [Thinking in DevOps](./blogs/Introduction-To-DevOps/Thinking-DevOps/README.md)       |- | [Lab](./blogs/Introduction-To-DevOps/Thinking-DevOps/1.Social-coding-principle.md)  |
| 3.1  | [Social Coding Principle](/blogs/Introduction-To-DevOps/Thinking-DevOps/1.Social-coding-principle.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Thinking-DevOps/Quizz.md)| |
| 3.2  | [Git Repository Guideline](/blogs/Introduction-To-DevOps/Thinking-DevOps/2.Git-Repository-Guideline.md) |    - |  [Quizz](/blogs/Introduction-To-DevOps/Thinking-DevOps/Quizz.md) |
| 3.3  | [Work in small batches](/blogs/Introduction-To-DevOps/Thinking-DevOps/3.Work-in-small-batches.md) |    - |   [Quizz](/blogs/Introduction-To-DevOps/Thinking-DevOps/Quizz.md)|
| 3.4  | [Minimum Viable Product - MVP](/blogs/Introduction-To-DevOps/Thinking-DevOps/4.Minimum-Viable-Product.md) |    - |   [Quizz](/blogs/Introduction-To-DevOps/Thinking-DevOps/Quizz.md)|
| 3.5  | [Test Driven Development](/blogs/Introduction-To-DevOps/Thinking-DevOps/5.Test-Driven-Development.md) |    - |  [Quizz](/blogs/Introduction-To-DevOps/Thinking-DevOps/Quizz.md) |
| 3.6  | [Behavior Driven Development](/blogs/Introduction-To-DevOps/Thinking-DevOps/6.Behavior-Driven-Development.md) | - |   [Quizz](/blogs/Introduction-To-DevOps/Thinking-DevOps/Quizz.md)|
| 3.7  | [Cloud Native Microservices](/blogs/Introduction-To-DevOps/Thinking-DevOps/7.Cloud-Native-Microservices.md) |    - |  [Quizz](/blogs/Introduction-To-DevOps/Thinking-DevOps/Quizz.md) |
| 3.8  | [Designing For Failure](/blogs/Introduction-To-DevOps/Thinking-DevOps/8.Designing-For-Failure.md) |    - |  [Quizz](/blogs/Introduction-To-DevOps/Thinking-DevOps/Quizz.md) |
| 4  | [**Working in DevOps**](./blogs/Introduction-To-DevOps/Working-DevOps/README.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Thinking-DevOps/Quizz.md)| |
| 1  | [Case Against Taylorism in Software Development](/blogs/Introduction-To-DevOps/Working-DevOps/1-Moving-beyond-taylorism-and-silos.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Working-DevOps/11-Quiz.md)| |
| 2  | [Software Engineering vs. Civil Engineering](/blogs/Introduction-To-DevOps/Working-DevOps/2-software-engineering-vs-civil-engineering.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Working-DevOps/11-Quiz.md)| |
| 3  | [Required DevOps Behaviors](/blogs/Introduction-To-DevOps/Working-DevOps/3-Required-DevOps-behaviors.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Working-DevOps/11-Quiz.md)| |
| 3A  | [Choose DevOps Behaviors](/blogs/Introduction-To-DevOps/Working-DevOps/3Q-Choose-DevOps-Behaviors.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Working-DevOps/11-Quiz.md)| |
| 4  | [Infrastructure as Code (IaC)](/blogs/Introduction-To-DevOps/Working-DevOps/4-infrastructure-as-code.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Working-DevOps/11-Quiz.md)| |
| 5  | [Continuous Integration](/blogs/Introduction-To-DevOps/Working-DevOps/5-continuous-integration-cd.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Working-DevOps/11-Quiz.md)| |
| 6  | [Continuous Delivery](/blogs/Introduction-To-DevOps/Working-DevOps/6-continuous-delivery.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Working-DevOps/11-Quiz.md)| |
| 7  | [Organizational Impact of DevOps](/blogs/Introduction-To-DevOps/Working-DevOps/7-organizational-impact-of-devops.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Working-DevOps/11-Quiz.md)| |
| 8  | [There is no DevOps Team](/blogs/Introduction-To-DevOps/Working-DevOps/8-there-is-no-devops-team.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Working-DevOps/11-Quiz.md)| |
| 9  | [Everyone is Responsible for Success](/blogs/Introduction-To-DevOps/Working-DevOps/9-everyone-is-responsible-for-success.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Working-DevOps/11-Quiz.md)| |
| 10 | [Discussion and summary](/blogs/Introduction-To-DevOps/Working-DevOps/10-devops-metrics.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Working-DevOps/11-Quiz.md)| |
| 11 | [Quiz: Test Your Knowledge](/blogs/Introduction-To-DevOps/Working-DevOps/11-Quiz.md) | -   | [Quizz](/blogs/Introduction-To-DevOps/Working-DevOps/11-Quiz.md)| |
| -  |       [People in DevOps](./blogs/3-people-in-devops.md)       |           -                            | -  |
| 4  |       [Assses your software developement process](./blogs/4-assess-software-development-process.md)       |           -                            | -  |
| 5  |       [Product and Technology in DevOps](./blogs/5-product-technology.md)       |           -                            | -  |
| 6  |       [Linux Fundamentals](./blogs/6-linux-fundamentals.md)       |           -                            | -  |
| 7  |       [Network Fundamentals](./blogs/7-network-fundamentals.md)       |           -                            | -  |
| 8  |       [Applications Fundamentals](./blogs/8-applications-fundamentals.md)       |           -                            | -  |
| 9  |       [Git fundamentals](./blogs/9-git-fundamentals.md)       |           -                            | -  |
| 10  |       [Database Fundamentals](./blogs/10-database-fundamentals.md)       |           -                            | -  |
| 11  |       [Security Fundamentals](./blogs/11-security-fundamentals.md)       |           -                            | -  |
| 12  |       [2 Tier applications](./blogs/12-2-tier-applications.md)       |           -                            | -  |
| II |              **Linux**              |
| 13  |       [Introduction to Linux](./blogs/13-introduction-linux.md)       |           -                            | -  |
| 14  |       [Working with shell 1](./blogs/14-working-with-shell-1.md)       |           -                            | -  |
| 15  |       [Linux core concepts](./blogs/15-linux-core-concepts.md)       |           -                            | -  |
| 16  |       [Package management](./blogs/16-package-management.md)       |           -                            | -  |
| 17  |       [Working with shell 2](./blogs/17-working-with-shell-2.md)       |           -                            | -  |
| 18  |       [Networking](./blogs/18-networking.md)       |           -                            | -  |
| 19  |       [Security and Permissions](./blogs/19-security-permissions.md)       |           -                            | -  |
| 20  |       [Service management with SYSTEMD](./blogs/20-service-management-systemd.md)       |           -                            | -  |
| 21  |       [Storage in Linux](./blogs/21-storage-in-linux.md)       |           -                            | -  |
| III |              **Shell scripting**              |
| 22  |       [Shell condition](./blogs/22-shell-condition.md)       |           -                            | -  |
| 23  |       [Shell flow control](./blogs/23-shell-flow-control.md)       |           -                            | -  |
| 24  |       [Shell scripting project](./blogs/24-shell-scripting-project.md)       |           -                            | -  |
| IV |            **CI/CD Pipelines**             | [Azure DevOps](./blogs/azure-devops.md) | [Create a Pipeline](./blogs/create-pipeline.md)|
| 25  |            [Introduction to CI/CD](./blogs/25-introduction-cicd.md)             |           [Azure Pipelines](./blogs/azure-pipelines.md)             | [Lab](./blogs/25-cicd-lab.md) |
| V |              **Docker Container**              |
| VI |              **Kubernetes Basics**              | [Kubernetes Setup Guide](./blogs/kubernetes-setup-guide.md)| [Explore Kubernetes](./blogs/explore-kubernetes.md) |
| 26  |            [Understanding Pods, Nodes, and Services](./blogs/26-pods-nodes-services.md)             |           [Kubernetes Commands](./blogs/kubernetes-commands.md)         | [Lab](./blogs/26-kubernetes-lab.md) |
| 27  |            [Kubernetes Deployment Strategies](./blogs/27-deployment-strategies.md)             |           [Blue-Green Deployment](./blogs/blue-green-deployment.md) / [Canary Release](./blogs/canary-release.md)             | [Lab](./blogs/27-kubernetes-lab.md) |
| VII |       [**Cloud Platforms Overview**](./blogs/cloud-platforms-overview.md) |||
| 28  |                [Introduction to AWS and Azure](./blogs/28-aws-azure.md)                 |                       [AWS Setup Guide](./blogs/aws-setup-guide.md) / [Azure Basics](./blogs/azure-setup-guide.md)                      | [Lab](./blogs/28-cloud-lab.md) |
| 29  |                   [Multi-Cloud Environments](./blogs/29-multi-cloud-environments.md)                   |        [Multi-Cloud Strategies](./blogs/multi-cloud-strategies.md)        | [Lab](./blogs/29-cloud-lab.md) |
| 30  |            [Infrastructure as Code with Terraform](./blogs/30-infrastructure-as-code-terraform.md)             |           [Terraform Basics](./blogs/terraform-basics.md) / [AWS IaC](./blogs/aws-iac.md)             | [Lab](./blogs/30-terraform-lab.md) |
| VIII |              **GitOps**              |
| 31  |       [GitOps and Version Control](./blogs/31-gitops-version-control.md)       |            [Git Basics](./blogs/git-basics.md) /  [GitOps with Kubernetes](./blogs/gitops-kubernetes.md)                             |  |
| IX |            [**Automation with Scripting**](./blogs/automation-with-scripting.md)             | [Bash Scripting](./blogs/bash-scripting.md) | [Automate with Bash](./blogs/automate-with-bash.md) |
| 32  |            [Advanced Bash Techniques](./blogs/32-advanced-bash.md)             |           [Loops and Conditionals](./blogs/bash-loops-conditionals.md)             | [Lab](./blogs/32-advanced-bash-lab.md) |
| X |              **Programming with Golang**              |
| 33  |       [Basic Go](./blogs/33-basic-go.md)       |           -                            | -  |
| XI |            **Python for DevOps**             |||
| 34  |            [Introduction to Python for DevOps](./blogs/34-python-for-devops.md)             |           [Automating with Python](./blogs/automate-python.md)             | [Lab](./blogs/34-python-lab.md) |
| XII  |            **Use case** | | |
| 35  |            [DevOps Best Practices](./blogs/35-devops-best-practices.md)             |           [Documentation and Testing](./blogs/documentation-testing.md)    | |


## Each lesson contains

* Pre-reading material
* Practical labs to apply the material you have learned.
* Quizzes to test your knowledge and understanding.

## Getting Started

- We have created a [setup lesson](./lessons/0-course-setup/setup.md) to help you with setting up your development environment.
- How to [Run the code in a VSCode or Codepace](./lessons/0-course-setup/how-to-run.md).

Don't forget to star (🌟) this repo to find it easier later.


## Help Wanted

Do you have suggestions or found spelling or code errors? Raise an issue or create a pull request.

## Special Thanks

* **🙏 Core Contributors:** [Contributors](https://github.com/phuongvo9/phuongvo9.github.io/graphs/contributors)

## Inspired by Curricula from Microsoft Learn

*Special thanks to Microsoft Learn for their inspiring curricula. Their comprehensive and beginner-friendly courses have motivated me to create this DevOps curriculum to help others embark on their DevOps journey.*

* [Machine Learning for Beginners](https://aka.ms/ml4beginners)
* [Generative AI for Beginners](https://aka.ms/genai-beginners)
* [Web Dev for Beginners](https://aka.ms/webdev-beginners)
* [Cybersecurity for Beginners](https://aka.ms/security-101)
* [ML for Beginners](https://aka.ms/ml-beginners)
* [Data Science for Beginners](https://aka.ms/datascience-beginners)
* [AI for Beginners](https://aka.ms/ai-beginners)
* [Cybersecurity for Beginners](https://github.com/microsoft/Security-101)
* [IoT for Beginners](https://aka.ms/iot-beginners)
* [XR Development for Beginners](https://github.com/microsoft/xr-development-for-beginners)
* [Mastering GitHub Copilot for AI Paired Programming](https://aka.ms/GitHubCopilotAI)

# My courses besides DevOps

* [AI Prompting Essentials](./courses/AI-Prompting-Essentials/README.md)