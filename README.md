# Docker-in-Jenkins

## **Project Overview**
This project demonstrates the use of  jenkins to push image to DockerHub Repository and Nexus Repository .
---

## **Diagrammatic Presentation**

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

### Push Image to DockerHub Repository
- Made Docker available in Jenkins container (mount docker runtime inside container as a volume)

  ![image](https://github.com/user-attachments/assets/e9ddeb31-0366-447d-84f9-9bd99b99fe5d)

- Fixed permissions on docker.sock

  ![image](https://github.com/user-attachments/assets/dd6d7c5f-c011-430a-9d0e-d4806dc5c761)

- Configured Job to build Docker Image

  ![image](https://github.com/user-attachments/assets/dce03a8e-e5fd-4a9a-9d2d-35d5703fdbc7)

- Configured Job to push Image to DockerHub
    - Prerequisite: Account on DockerHub
    - Created a repository on DockerHub
    - Created Credentials for DockerHub in Jenkins UI
    - Tag Docker Image with your DockerHub repository, login and push to repository

  ![image](https://github.com/user-attachments/assets/aadae8dc-9bd6-4b22-8abd-d04db2819c0a)


  ![image](https://github.com/user-attachments/assets/640c9c82-cf73-4024-880a-b4bdbf876f1a)


      
###  push Image to Nexus Repository
- Configured “insecure-registries” on Droplet server (daemon.json file)
- Fixed permission for docker.sock again after restart of Jenkins container

  ![image](https://github.com/user-attachments/assets/2db903b8-b8ab-40d9-b27b-0a0b2e922995)


  ![image](https://github.com/user-attachments/assets/85ceede3-4b85-45ea-a282-7cdd0e3cb1c7)

- Created Credentials for Nexus in Jenkins UI
- Tag Docker Image with your Nexus host and repository, login and push to repository

  ![image](https://github.com/user-attachments/assets/c90c0fcf-e10b-439a-99d5-9684da2d7433)


  ![image](https://github.com/user-attachments/assets/f689259f-aa5c-4b2a-9df9-ba7eb318c66e)


  ![image](https://github.com/user-attachments/assets/a93b0121-f9c7-4ca0-bc90-c8844423929c)


  






