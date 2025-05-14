# Docker-in-Jenkins

## **Project Overview**
This project demonstrates using jenkins to push image to DockerHub Repository and Nexus Repository .
---

## **Features**

### push Image to DockerHub Repository
- Made Docker available in Jenkins container (mount docker runtime inside container as a volume)
- Fixed permissions on docker.sock
- Configured Job to build Docker Image
- Configured Job to push Image to DockerHub
    - Prerequisite: Account on DockerHub
    - Created a repository on DockerHub
    - Created Credentials for DockerHub in Jenkins UI
    - Tag Docker Image with your DockerHub repository, login and push to repository
