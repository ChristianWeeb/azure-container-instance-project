Cloud Platform: Microsoft Azure
Service: Azure Container Instances (ACI)
Container Runtime: Docker/Linux
Networking: Public endpoint with custom DNS
Image: Microsoft sample container (aci-helloworld)

Implementation Steps
1. Created Resource Group

Resource group name: rg-container-demo
Region: East US

2. Deployed Container Instance

Container name: my-web-container
Image source: Quickstart images
Image: mcr.microsoft.com/azuredocs/aci-helloworld
OS type: Linux
Size: 1 vCPU, 1.5 GB memory

3. Configured Networking

Networking type: Public
DNS name label: Custom DNS name
Port: 80 (HTTP)
Public accessibility enabled

4. Verified Deployment

Confirmed container status: Running
Accessed public FQDN
Tested web application functionality
