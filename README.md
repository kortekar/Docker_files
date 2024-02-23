# Docker 🐳
Docker Image Commands

### ✅ List Images
docker images



### ✅ Pull Image from Registry
docker pull <image_name>:<tag>
## Example: docker pull ubuntu:latest



### ✅ Build Image from Dockerfile
docker build -t <image_name>:<tag> .
## Example: docker build -t my-custom-image:latest .



### ✅ Remove Image
docker rmi <image_id or image_name>
## Example: docker rmi my-custom-image:latest

Docker Container Commands

### ✅ Run Container
docker run -d --name <container_name> -p <host_port>:<container_port> <image_name>:<tag>
## Example: docker run -d --name my-container -p 8080:8080 my-custom-image:latest



### ✅ List Running Containers
docker ps



### ✅ List All Containers (Running and Stopped)
docker ps -a



### ✅ Stop Container
docker stop <container_id or container_name>
## Example: docker stop my-container



### ✅ Remove Container
docker rm <container_id or container_name>
## Example: docker rm my-container


### ✅ Inspect Container
docker inspect <container_id or container_name>
## Example: docker inspect my-container




Docker Registry Commands

### ✅ Login to Docker Hub
docker login



### ✅ Push Image to Registry
docker push <image_name>:<tag>
## Example: docker push my-custom-image:latest



Docker Volume Commands

### ✅ List Volumes
docker volume ls



### ✅ Create a Volume
docker volume create <volume_name>
## Example: docker volume create my-volume



### ✅ Remove Volume
docker volume rm <volume_name>
## Example: docker volume rm my-volume


