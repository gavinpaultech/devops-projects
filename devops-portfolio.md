# 🚀 DevOps Project Showcase



Welcome to my **DevOps Project Showcase**! This repository contains a collection of hands-on projects where I applied my knowledge in various DevOps practices. These projects cover a wide range of technologies such as **CI/CD pipelines**, **cloud infrastructure management**, **monitoring**, **automation with Ansible**, and much more.

Each project below is linked to its **individual repository**, where you can find the full configurations, scripts, and documentation used throughout the project. Feel free to explore, clone, or contribute!

For more projects, follow my [GitLab Profile](https://gitlab.com/gavin.faber), where I regularly upload new work related to DevOps and automation.

---

## DevOps Tools Used

- **Version Control:** Git
- **Build Tools:** Maven, Gradle
- **Artifact Repo Manager:** Nexus
- **IDE:** IntelliJ, VS Code, PyCharm
- **Cloud & Infrastructure:** DigitalOcean, AWS, Linode LKE
- **Containerization:** Docker, Kubernetes, Helm, Amazon ECR
- **CI/CD:** Jenkins
- **Programming & Scripting:** Python, Java, Node.js, Groovy
- **Infrastructure as Code:** Terraform
- **Configuration Management:** Ansible
- **Monitoring & Logging:** Prometheus, Grafana

## Project Structure

You can find all the repositories for these projects on GitLab: gavin-devops-projects on [GitLab](https://gitlab.com/gavin-devop-projects)! 🦊


```bash
gavin-devops-projects/
├── 03-git.md         # Link to Git repo in GitLab
├── 04-build-tools.md # Link to Build Tools repo in GitLab
├── 05-cloud.md       # Link to Cloud repo in GitLab
├── 06-nexus.md       # Link to Nexus repo in GitLab
├── 07-docker.md      # Link to Docker repo in GitLab
├── 08-jenkins.md     # Link to Jenkins repo in GitLab
├── 09-aws.md         # Link to AWS repo in GitLab
├── 10-kubernetes.md  # Link to Kubernetes repo in GitLab
├── 11-eks.md         # Link to EKS repo in GitLab
├── 12-terraform.md   # Link to Terraform repo in GitLab
├── 13-python.md      # Link to Python repo in GitLab
├── 14-automation-with-python.md  # Link to Automation with Python repo in GitLab
├── 15-ansible.md     # Link to Ansible repo in GitLab
├── 16-prometheus.md  # Link to Prometheus repo in GitLab
```

## Projects Overview

Below are the details of each project and what was accomplished.


## 🌐 Cloud & IaaS Projects

### 🔹 Deploy Java App on DigitalOcean  
**Tech:** DigitalOcean, Linux, Java, Gradle  
**Description:**  Provisioned a secure Droplet, created users, and deployed a Java Gradle application.

### 🔹 Host Maven & Gradle Artifacts in Nexus  
**Tech:** Nexus, Linux, Gradle, Maven, DigitalOcean  
**Description:**  Installed Nexus, managed access, and published artifacts using both build tools.

---

## 🐳 Docker & Containerization Projects

### 🔹 Local Dev with Docker  
**Tech:** Docker, Node.js, MongoDB, MongoExpress  
**Description:**  Dockerized a Node.js app and set up containers for MongoDB & MongoExpress.

### 🔹 Multi-Container Setup with Docker Compose  
**Tech:** Docker, MongoDB, MongoExpress  
**Description:**  Used `docker-compose` to orchestrate local services.

### 🔹 Deploy Docker App Remotely  
**Tech:** Docker, Node.js, Amazon ECR  
**Description:**  Built & pushed Docker image to ECR, then deployed via Compose on server.

### 🔹 Docker Image to Nexus  
**Tech:** Docker, Nexus, DigitalOcean  
**Description:**  Set up a private Docker repo in Nexus and pushed custom images securely.

### 🔹 Persist Data with Docker Volumes  
**Tech:** Docker, MongoDB  
**Description:**  Ensured data persistence with mounted volumes for MongoDB.

### 🔹 Run Nexus as Docker Container  
**Tech:** Docker, Nexus, DigitalOcean  
**Description:**  Deployed Nexus inside a container on a remote Droplet.

---

## ⚙️ CI/CD Automation with Jenkins

### 🔹 Jenkins in Docker  
**Tech:** Jenkins, Docker, DigitalOcean  
**Description:**  Containerized Jenkins for quick setup and isolation.

### 🔹 Jenkins CI Pipeline  
**Tech:** Jenkins, Java, Maven, Docker, Git  
**Description:**  Built a CI pipeline: Compile → Dockerize → Push image to registry.

### 🔹 Shared Jenkins Library  
**Tech:** Jenkins, Groovy, Git  
**Description:**  Modularized repeated pipeline logic into a shared library.

### 🔹 GitLab Webhook Integration  
**Tech:** Jenkins, GitLab  
**Description:**  Set up webhook triggers to automate pipeline runs.

### 🔹 Dynamic Versioning in Pipelines  
**Tech:** Jenkins, Git, Docker, Maven  
**Description:**  Auto-versioning based on Git metadata and pushing updated tags.

---

## ☁️ AWS DevOps Projects

### 🔹 Manual EC2 Deployment  
**Tech:** AWS EC2, Docker  
**Description:**  Configured security groups and manually deployed a containerized app.

### 🔹 Jenkins → EC2 CD Pipeline  
**Tech:** Jenkins, Docker, Git, AWS  
**Description:**  SSH into EC2 from Jenkins and deploy updated builds.

### 🔹 Docker Compose CD from Jenkins  
**Tech:** Docker Compose, Jenkins, AWS  
**Description:**  Automated deployment via `docker-compose` in a CI/CD pipeline.

### 🔹 AWS CLI Scripting  
**Tech:** AWS CLI, Linux  
**Description:**  Automated EC2, IAM, and S3 tasks using CLI scripts.

---

## ☸️ Kubernetes Projects

### 🔹 Local K8s Cluster with MongoDB  
**Tech:** Kubernetes, Minikube, MongoDB  
**Description:**  Deployed MongoDB using K8s configs, secrets, and volumes.

### 🔹 Helm-Based Stateful Deployments  
**Tech:** Helm, Linode LKE, MongoDB  
**Description:**  Used Helm to deploy and manage stateful workloads on cloud K8s.

### 🔹 Secure Mosquitto with K8s  
**Tech:** Kubernetes, Docker, Mosquitto  
**Description:**  Secured Mosquitto MQTT broker using ConfigMaps and Secrets.

### 🔹 Deploy from ECR to K8s  
**Tech:** Kubernetes, AWS ECR, Helm  
**Description:**  Pulled Docker images from ECR and deployed to cluster.

### 🔹 Production Microservices with Best Practices  
**Tech:** Kubernetes, Redis, Linode  
**Description:**  Orchestrated multiple services with RBAC, readiness probes, and autoscaling.

### 🔹 Helm Charts & Helmfile  
**Tech:** Helm, Helmfile  
**Description:**  Templated reusable Helm charts and used Helmfile for complex deployments.

---

## 🧬 AWS EKS Kubernetes Projects

### 🔹 Create EKS Cluster  
**Tech:** AWS EKS, Kubernetes  
**Description:**  Provisioned EKS cluster with managed node groups.

### 🔹 Run on AWS Fargate  
**Tech:** AWS Fargate, Kubernetes  
**Description:**  Deployed workloads without managing EC2 instances.

### 🔹 eksctl Automation  
**Tech:** eksctl, AWS, Kubernetes  
**Description:**  Used `eksctl` to script full cluster provisioning.

### 🔹 Jenkins Deploy to EKS  
**Tech:** Jenkins, kubectl, EKS  
**Description:**  Deployed from Jenkins pipelines to EKS via Kubernetes CLI.

---

## 🌱 Infrastructure as Code with Terraform

### 🔹 Automate Infra on AWS  
**Tech:** Terraform, Docker, AWS  
**Description:**  Provisioned VPCs, EC2s, and deployed containerized apps.

### 🔹 Modular Terraform Design  
**Tech:** Terraform, AWS  
**Description:**  Created reusable module structures for better scalability.

### 🔹 Provision EKS with Terraform  
**Tech:** Terraform, AWS EKS  
**Description:**  Fully automated EKS provisioning.

### 🔹 CI/CD with Jenkins + Terraform  
**Tech:** Jenkins, Terraform, Docker  
**Description:**  Built CI/CD to provision infra and deploy code.

### 🔹 Remote State with S3  
**Tech:** Terraform, S3  
**Description:**  Managed state across teams using shared S3 backend.

---

## 🐍 Python Automation Projects

### 🔹 Countdown Timer  
**Tech:** Python  
**Description:**  Simple terminal countdown to any target date.

### 🔹 Excel Automation  
**Tech:** Python  
**Description:**  Processed spreadsheets with Python automation scripts.

### 🔹 GitLab API Integration  
**Tech:** Python, GitLab API  
**Description:**  Fetched and displayed public repo info from GitLab.

### 🔹 EC2 Monitoring Script  
**Tech:** Python, Boto3  
**Description:**  Logged EC2 health status continuously.

### 🔹 Tag Automation for EC2  
**Tech:** Python, Boto3  
**Description:**  
Assigned tags to instances automatically on launch.

### 🔹 EKS Cluster Info Display  
**Tech:** Python, Boto3  
**Description:**  Printed detailed EKS cluster information.

### 🔹 EC2 Backup & Restore  
**Tech:** Python, Boto3  
**Description:**  Automated volume snapshot and restore flows.

### 🔹 Website Monitoring & Auto-Recovery  
**Tech:** Python, Docker  
**Description:**  Checked uptime, sent alerts, and restarted services if down.

---

## 🧰 Configuration Management with Ansible

### 🔹 Deploy App with Ansible  
**Tech:** Ansible, Node.js, DigitalOcean  
**Description:**  Automated end-to-end deployment on a Linux server.

### 🔹 Nexus Setup with Ansible  
**Tech:** Ansible, Nexus  
**Description:**  Provisioned and configured Nexus using Ansible playbooks.

### 🔹 Ansible + Terraform Integration  
**Tech:** Ansible, Terraform, AWS  
**Description:**  Used Terraform to provision infra and Ansible to configure it.

### 🔹 Dynamic Inventory for EC2  
**Tech:** Ansible, AWS  
**Description:**  Generated dynamic host inventory based on EC2 metadata.


### 🔹 Ansible Integration in Jenkins  
**Tech:** Ansible, Jenkins, DigitalOcean, AWS, Boto3, Docker, Java, Maven, Linux, Git  
**What I Accomplished:**  
- Created and configured a dedicated server for Jenkins.  
- Set up a dedicated server for Ansible Control Node.  
- Wrote an Ansible Playbook to configure two EC2 instances.  
- Configured Jenkins to execute the Ansible Playbook as part of a CI/CD pipeline, automating the process.  


### 🔹 Structure Playbooks with Ansible Roles  
**Tech:** Ansible, Docker, AWS, Linux  
**What I Accomplished:**  
- Broke down large Ansible Playbooks into smaller, reusable roles for better organization and maintainability.  


## ☁️ Monitoring with Prometheus

### 🔹 Install Prometheus Stack in Kubernetes  
**Tech:** Prometheus, Kubernetes, Helm, AWS EKS, eksctl, Grafana, Linux  
**What I Accomplished:**  
- Set up an EKS cluster using eksctl.  
- Deployed Prometheus, Alert Manager, and Grafana in the Kubernetes cluster using Helm charts, enabling robust monitoring and alerting.  


### 🔹 Configure Alerting for our Application  
- **Tech:** Prometheus, Kubernetes, Linux  
- **What I Accomplished:**  
    - Configured the Prometheus monitoring stack to alert when CPU usage exceeds 50% or if a Pod fails to start.  
    - Set up alert rules in Prometheus and configured Alertmanager with an email receiver to notify on critical issues.  


### 🔹 Configure Monitoring for a Third-Party Application  
**Tech:** Prometheus, Kubernetes, Redis, Helm, Grafana  
**What I Accomplished:**  
- Deployed Redis in Kubernetes and used Prometheus Exporter to monitor Redis' health.  
- Configured alert rules for Redis downtime and connection limits.  
- Imported a Grafana Dashboard for Redis to visualize monitoring data in real-time.  


### 🔹 Configure Monitoring for Own Application  
**Tech:** Prometheus, Kubernetes, Node.js, Grafana, Docker, Docker Hub  
**What I Accomplished:**  
- Configured a Node.js application to expose application metrics using the Prometheus client library.  
- Deployed the Node.js application with a metrics endpoint to Kubernetes.  
- Set up Prometheus to scrape the exposed metrics and visualize the data on a Grafana Dashboard.  


---