# Docker Practice

This repository contains my Docker learning and hands-on practice.

## Topics Covered
- Docker installation
- Docker images
- Docker containers
- Dockerfile basics

## Commands

docker --version  
docker pull nginx  
docker images  
docker run -d -p 8080:80 nginx  
docker ps  
docker stop <container_id>  

## Sample Dockerfile

FROM nginx:latest  
COPY index.html /usr/share/nginx/html/index.html  
EXPOSE 80  

## Learning Outcome
- Learned Docker basics  
- Understood containers and images  
- Deployed a simple web app using Docker  
