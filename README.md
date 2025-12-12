# Docker Commands: Complete Guide.

A complete, and easy-to-understand Docker command reference for installation, container management, image handling, logs, networking, and Docker Hub deployment. Perfect for DevOps beginners and cloud engineers using Linux, Ubuntu EC2, Windows, or macOS.

---
## Step 1. Install Docker (Ubuntu)

```bash
sudo apt update
sudo apt install docker.io -y
sudo systemctl start docker
sudo systemctl enable docker
docker --version
```
----
## step 2. Check Docker Version
```
docker --version
```
---
## Step 3. Visit Docker Hub

Before pulling, tagging, or pushing Docker images, you must create a Docker Hub account.

 https://hub.docker.com/signup

  Fill the required details:
- Username  
- Email  
- Password
---
  ## Step 4. List Docker Image 
```
docker images
docker image ls
```
---
## Step 5. Check Image History
```
docker history <image-name> or <image-id>
```
---
## Step 6. List Containers
```
docker ps
```
---
## Step 7. All Contaniers 
```
docker ps -a
```
---
## Step 8. Pull an Image
```
docker pull <image-name>
```
---
## Step 9. Run a Container
```
docker run <image-name>
```
---
## Step 10. Run Contanier In Background
```
docker run -d <image-name>
```
---
## Step 11. Run Conatiner With Custom Name 
```
docker run --name <container-name> -d <image-name>
```
---
## Step 12. Stop & Start Containers
```
docker start <conatiner-id>
docker stop <conatiner-id>
```
## Stop all running container 
```
docker stop $(contanier-id)
```
---

## Step 13. Remove Docker Images
```
docker rmi <image-name>
docker rmi -f <image-name>
```
## Remove Multiple Image 
```
docker rmi image1 image2 image3
```
---
## Step 14. Remove a Contanier
```
docker rm <conatnier-id>
```
## Remove All Contanier 
```
docker rm $(docker ps -aq)
```
## Remove Multiple Contanier
```
docker rm container1 conatnier2 contanier3
```
---















  
