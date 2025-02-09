# DevOps CI/CD Pipeline for Containerized Applications Using Jenkins, Docker, Kubernetes, Helm

![CI/CD Pipeline](CICD%20for%20Containers.png)

## Overview
This project implements a CI/CD pipeline for containerized applications using **Jenkins, Docker, Kubernetes, Helm, SonarQube, and Nexus Repository**. The pipeline automates the software development lifecycle, including **code integration, testing, security scanning, artifact storage, and deployment to Kubernetes clusters**.

## Technology Stack
- **CI/CD Tool:** Jenkins
- **Containerization:** Docker
- **Container Orchestration:** Kubernetes (K8s) with Helm
- **Infrastructure:** AWS EC2 instances
- **Code Analysis:** SonarQube
- **Artifact Repository:** Nexus
- **Source Code Management:** GitHub
- **Notifications:** Slack Webhook
- **Build Tools:** Maven/Gradle
- **Security:** Kubernetes RBAC, IAM roles, and security groups

## Workflow
1. **Developers push code** → GitHub Webhook triggers Jenkins.
2. **Jenkins fetches the latest code** → Runs unit tests & SonarQube analysis.
3. **Build a Docker image** → Push it to DockerHub.
4. **Artifact stored in Nexus Repository**.
5. **Deploy application using Helm Charts on Kubernetes**.
6. **Slack notifications** for success or failure.

## Benefits
✅ **Automated CI/CD** – Reduces manual effort, improving efficiency.  
✅ **Improved Code Quality** – SonarQube ensures high-quality, secure code.  
✅ **Scalability** – Kubernetes auto-scales based on traffic demand.  
✅ **Faster Deployments** – Jenkins automates the entire process.  
✅ **Version Control** – Nexus stores build artifacts for rollback.  

## Conclusion
This CI/CD pipeline ensures that **code changes are automatically built, tested, secured, and deployed** to production with minimal human intervention. The integration of **Jenkins, Docker, Kubernetes, Helm, and SonarQube** enhances software reliability, accelerates release cycles, and improves **developer productivity**.



## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

## Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
## Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql


