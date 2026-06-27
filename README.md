# Cloud-and-Containers
## Microservices Containerization Assessment
## 1. Dockerfile Creation
### Created Cloud-and-Containers repository in Github and cloned the repository locally to perform the assisgnment.
### Cloned microserivices-task repository from Mohan's Github account for source code and copied microservices folder locally to my repository and pushed it to github.
### <img width="696" height="920" alt="image" src="https://github.com/user-attachments/assets/3d7f5663-acf0-4cae-909d-ad79e417197c" />
### Creating 4 Dockerfile for four different services (user service, product service, order service, gateway service)
### Dockerfile for User Service -->
### <img width="897" height="455" alt="image" src="https://github.com/user-attachments/assets/ded50e79-4dfd-42e5-b365-7563f769cbb4" />
### Dockerfile for Product Service -->
### <img width="922" height="461" alt="image" src="https://github.com/user-attachments/assets/3ef670a4-3f83-458f-96e6-276f9b4817e0" />
### Dockerfile for Order Service -->
### <img width="912" height="411" alt="image" src="https://github.com/user-attachments/assets/9a828912-651f-487a-88c1-245fa5deafa7" />
### Dockerfile for Gateway Service -->
### <img width="785" height="412" alt="image" src="https://github.com/user-attachments/assets/a3f70f35-ce1c-4d20-a960-606ba6724f17" />
## 2. Docker Compose Configuration
### Now, create the Docker compose file to containerize all the 4 services and to orchestrate them. Here is my Docker-compose.yml file.
### <img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/99186e11-2858-49be-97e5-76b63345b8f0" />
## 3. Local Testing & Validation 
### Run the application using docker-compose up on your local machine to ensure all services start correctly.
#### Run Command --> docker compose up -d
### I will now get the below output after running this command.
### <img width="1086" height="291" alt="image" src="https://github.com/user-attachments/assets/f27ca2d9-d4b3-4be3-a525-dcf958edb770" />
### Run docker ps command to list all the running containers created by Docker-compose.yml file
#### Run Command --> docker ps
### <img width="1602" height="207" alt="image" src="https://github.com/user-attachments/assets/90f6746f-13ca-4198-a8df-57fa800cd0fd" />
### Check all the services by running the docker compose ls command
#### Run Command --> docker compose ls
### <img width="1657" height="372" alt="image" src="https://github.com/user-attachments/assets/2f39e392-4f9b-4d13-9f29-a3ae4f43a469" />
### All the microservivces are created under shared network, run docker network ls command to verify.
#### Run Command --> docker network ls
### <img width="677" height="287" alt="image" src="https://github.com/user-attachments/assets/87a91208-b8f4-4115-89df-6a4d32c93f60" />
### Confirm accessibility via localhost on respective ports individually.
### Test User Service -->
### <img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/fd315f5a-1dad-407f-bea0-ef1dee376e54" />
### Test Product Service -->
### <img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/a7f3c863-9ab2-4ed0-81fb-21d3129a8d97" />
### Test Order Service -->
### <img width="1917" height="1072" alt="image" src="https://github.com/user-attachments/assets/186ffb11-1b90-4cdb-9444-91bb20c31b5c" />
###  Test Gateway Service -->
#### You can call the user serrvice from gateway service directly using API
### <img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/c4282a8a-985b-4a16-a895-4b9e1ebca5d8" />
#### You can call the product serrvice from gateway service directly using API
### <img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/5c89de33-1a95-47e4-9e52-960d30e2a846" />
#### You can call the order serrvice from gateway service directly using API
### <img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/8e2dd5a6-5b5e-40e5-8fd7-e67452f6e89f" />
## 4. Documentation
### I have explained everything in this readme file with screen shot of each steps.
### All the Dockerfiles and Docker-compose.yml file are placed in the GITHUB repo under Microservices folder
### please review and provide your feedback.
















