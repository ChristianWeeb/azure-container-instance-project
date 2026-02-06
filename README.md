# Azure Container Instance Deployment

## Project Overview
Deployed a containerized web application using Azure Container Instances, demonstrating serverless container deployment with public accessibility.

## 🌐 Live Application
**URL**: [your-fqdn].azurecontainer.io

## 🛠️ Technologies Used
- Microsoft Azure
- Azure Container Instances (ACI)
- Docker/Linux Containers
- Public DNS & Networking

## 📋 Implementation Steps

### 1. Created Resource Group
```bash
Resource group: rg-container-demo
Region: East US
```

### 2. Deployed Container Instance
- Container name: `my-web-container`
- Image: `mcr.microsoft.com/azuredocs/aci-helloworld`
- OS: Linux
- Size: 1 vCPU, 1.5 GB RAM

### 3. Configured Networking
- Public endpoint with custom DNS
- Port 80 (HTTP)

### 4. Verified Deployment
- Status: Running ✅
- Accessed via public URL

## ✨ Key Features
- Serverless container deployment
- Public HTTP endpoint
- Custom DNS configuration
- Pay-per-use pricing
- Rapid deployment (< 2 minutes)

## 💡 Skills Demonstrated
- Azure Container Instances
- Container orchestration
- Network configuration
- Serverless computing
- Cloud resource management

## 💰 Cost Analysis
- **Running**: ~$0.02-0.05/hour
- **Total**: < $1 with cleanup

## 📸 Screenshots

![Azure Portal - Container Running](screenshots/container-running.png)
![Live Application](screenshots/live-app.png)

## 🎓 Learning Outcomes
Successfully deployed containerized application to Azure, demonstrating modern cloud deployment patterns.

---

**Part of my Azure certification journey - AZ-900**
