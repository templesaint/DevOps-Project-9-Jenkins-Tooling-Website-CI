# Tooling Website Deployment Automation & Continuous Integration Using Jenkins

## Project Overview

This project is part of my DevOps engineering journey, where I built and configured a Jenkins-based Continuous Integration (CI) environment to automate application deployment processes.

The aim of this project was to move away from manual deployment approaches and understand how DevOps engineers use automation tools to create reliable, repeatable, and efficient software delivery workflows.

Through this project, I gained hands-on experience setting up cloud infrastructure, configuring Jenkins, managing Linux servers, establishing secure server communication, and preparing an automated deployment workflow.

The project demonstrates my practical understanding of:

- Cloud infrastructure setup
- Linux server administration
- Jenkins CI configuration
- Java environment management
- SSH authentication
- Repository integration
- Deployment automation concepts


---

# Project Objectives

The main objectives of this project were:

- Deploy Jenkins on an AWS EC2 server.
- Configure Jenkins as a Continuous Integration server.
- Install and configure Java dependencies required by Jenkins.
- Secure Jenkins access.
- Connect Jenkins with source code repositories.
- Configure SSH communication between servers.
- Create Jenkins automation jobs.
- Understand the workflow behind automated deployments.


---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| AWS EC2 | Cloud infrastructure hosting |
| Ubuntu Linux | Server operating system |
| Jenkins | Continuous Integration automation server |
| Java 11 | Jenkins runtime environment |
| Git | Source code management |
| SSH | Secure remote communication |
| NFS | Shared storage configuration |


---

# Project Architecture

The project follows this workflow:

```
Developer
    |
    |
Git Repository
    |
    |
Jenkins CI Server
    |
    |
SSH Connection
    |
    |
Deployment Server
    |
    |
Tooling Website
```


---

# Project Implementation Process

## 1. Preparing the Server Environment

The first step was preparing the Linux environment by updating the system packages and ensuring the server was ready for Jenkins installation.

This helped create a stable foundation before installing required dependencies.


![System Update](screenshots/ 01-System-Update-and-Upgrade.png)


---

# 2. AWS EC2 Instance Setup

I created an AWS EC2 instance that served as the Jenkins automation server.

The server was configured with the necessary access permissions and security settings required for remote administration.

![AWS EC2 Setup](./screenshots/02-AWS-EC2-Instance-Setup.png)


---

# 3. Installing Jenkins Server

After preparing the server, Jenkins was installed and configured.

This stage involved understanding how Jenkins operates as an automation server and how it manages continuous integration tasks.

![Jenkins Installation](./screenshots/03-Jenkins-Server-Installation.png)


---

# 4. Java Installation and Verification

Since Jenkins requires Java to run, I installed the required Java environment and verified that the installation was successful.

Understanding dependencies is an important part of DevOps because automation tools rely on properly configured environments.

![Java Version Check](./screenshots/04-Java-Version-Check.png)

![Java Installation](./screenshots/06-Java-Version-11-Installation.png)

![Updated Java Verification](./screenshots/15-Updated-Java-Version-Verification.png)


---

# 5. Jenkins Security Configuration

Security configuration was completed to ensure Jenkins was properly protected before connecting it with external resources.

![Jenkins Security Configuration](./screenshots/05-Jenkins-Security-Configuration.png)


---

# 6. Jenkins Repository Configuration

I configured Jenkins repository settings to prepare the environment for source code integration.

This step helped me understand how Jenkins connects development activities with automated workflows.

![Jenkins Repository Setup](./screenshots/12-Jenkins-Repository-Setup.png)


---

# 7. Jenkins Service Management

After installation, I enabled and verified that the Jenkins service was running successfully.

![Jenkins Service Enabled](./screenshots/09-Jenkins-Service-Enabled.png)


---

# 8. Accessing Jenkins Dashboard

The Jenkins web interface was accessed successfully after completing the installation and configuration process.

![Jenkins Welcome Page](./screenshots/10-Welcome-to-Jenkins.png)

![Jenkins Web Interface](./screenshots/11-Jenkins-Web-Interface.png)


---

# 9. SSH and NFS Configuration

One of the important parts of this project was establishing secure communication between servers.

I configured SSH access to allow Jenkins to communicate with deployment servers securely.

This is an essential concept in real-world DevOps environments where automation servers interact with application servers.

![SSH NFS Configuration](./screenshots/13-SSH-NFS-Server-Configuration.png)

![SSH Jenkins Configuration](./screenshots/14-SSH-Jenkins-Server-Configuration.png)


---

# 10. Jenkins Freestyle Project Creation

The final stage involved creating a Jenkins freestyle project.

This allowed Jenkins to execute automated tasks based on predefined configurations.

![Jenkins Freestyle Project](./screenshots/16-Jenkins-Freestyle-Project.png)


---

# Challenges Encountered

## Understanding Jenkins Dependencies

One of the challenges was understanding the relationship between Jenkins and its required dependencies.

I solved this by installing the correct Java version, verifying configurations, and testing Jenkins functionality step by step.


## Configuring Secure Communication

Setting up SSH communication between servers required proper key configuration and testing.

I solved this by generating SSH keys, configuring access permissions, and verifying successful server communication.


## Understanding CI Workflow

Moving from manual deployment thinking to automation required understanding how different DevOps components work together.

I approached the workflow by breaking it into smaller stages:

Infrastructure Setup → Jenkins Configuration → Repository Integration → Server Communication → Automation


---

# Skills Demonstrated

Through this project, I demonstrated practical knowledge of:

- AWS EC2 infrastructure
- Linux server administration
- Jenkins installation and configuration
- Continuous Integration concepts
- SSH authentication
- Git repository integration
- Deployment automation workflow
- Troubleshooting server configurations


---

# Key Lessons Learned

This project helped me understand that DevOps is not only about installing automation tools.

A successful CI/CD environment requires:

- Proper infrastructure planning
- Secure communication between systems
- Dependency management
- Automation thinking
- Continuous testing and improvement


---

# Future Improvements

The next improvements I would implement include:

- Creating Jenkins pipelines using Jenkinsfile
- Adding automated testing stages
- Integrating Docker containers
- Implementing Kubernetes deployment
- Adding monitoring tools such as Prometheus and Grafana
- Building a complete CI/CD pipeline


---

# Project Structure

```
DevOps-Project-7-Tooling-Website-Deployment-Automation

│
├── README.md
│
└── screenshots
    |
    ├── 01-System-Update-and-Upgrade.png
    ├── 02-AWS-EC2-Instance-Setup.png
    ├── 03-Jenkins-Server-Installation.png
    ├── 04-Java-Version-Check.png
    ├── 05-Jenkins-Security-Configuration.png
    ├── 06-Java-Version-11-Installation.png
    ├── 07-Java-Version-Verification.png
    ├── 08-Jenkins-GPG-Key-Configuration.png
    ├── 09-Jenkins-Service-Enabled.png
    ├── 10-Welcome-to-Jenkins.png
    ├── 11-Jenkins-Web-Interface.png
    ├── 12-Jenkins-Repository-Setup.png
    ├── 13-SSH-NFS-Server-Configuration.png
    ├── 14-SSH-Jenkins-Server-Configuration.png
    ├── 15-Updated-Java-Version-Verification.png
    └── 16-Jenkins-Freestyle-Project.png
```


---

# Author

## Essien Aniekan Temple-Saint

Aspiring DevOps Engineer focused on:

- Cloud Infrastructure
- Automation
- CI/CD
- Linux Administration
- DevOps Best Practices