# Docker-in-Jenkins

## **Project Overview**
This project demonstrates the use of  jenkins to push image to DockerHub Repository and Nexus Repository .
---

## **Features**

### Push Image to DockerHub Repository
- Made Docker available in Jenkins container (mount docker runtime inside container as a volume)
- Fixed permissions on docker.sock
- Configured Job to build Docker Image
- Configured Job to push Image to DockerHub
    - Prerequisite: Account on DockerHub
    - Created a repository on DockerHub
    - Created Credentials for DockerHub in Jenkins UI
    - Tag Docker Image with your DockerHub repository, login and push to repository
      
###  push Image to Nexus Repository
- Configured “insecure-registries” on Droplet server (daemon.json file)
- Fixed permission for docker.sock again after restart of Jenkins container
- Created Credentials for Nexus in Jenkins UI
- Tag Docker Image with your Nexus host and repository, login and push to repository
