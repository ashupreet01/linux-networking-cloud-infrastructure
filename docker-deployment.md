# Docker Web Application Deployment

## Overview

This practical demonstrates how to build and run a web application using Docker and Docker Compose.

## Docker Environment

Docker was installed and verified on Kali Linux.

Docker version was checked using:

docker --version

## Docker Image

A custom Docker image named docker-webapp was created using a Dockerfile.

The image contains an Nginx web server and the web page used for the practical.

## Docker Container

The Docker container was created and run using the docker-webapp image.

The container was mapped to port 8080 on the host system.

## Docker Compose

Docker Compose was used to define and run the web application service.

The service uses the docker-webapp image and maps:

Host Port 8080 → Container Port 80

## Testing

The deployed web application was tested using:

http://localhost:8080

The Nginx welcome page was displayed successfully, confirming that the container and web service were running correctly.

## Tools Used

- Kali Linux
- Docker
- Docker Compose
- Nginx
- VirtualBox

## Learning Outcome

I learned how to create a Docker image, run a container, configure port mapping and use Docker Compose to manage a web application.

## Conclusion

The practical successfully demonstrated containerized web application deployment using Docker and Docker Compose.
