# Docker & Containerization

## Overview

This module focuses on learning Docker and containerization concepts and deploying a web application using Docker.

## Key Objectives

1. Understand containers, virtual machines, Docker architecture, images, containers, and Dockerfile optimization.
2. Learn Docker commands, networking, volumes, persistent data, environment variables, and Docker Compose.
3. Containerize and deploy a web application using Docker.

## Topics Covered

### 1. Containers vs Virtual Machines
- Containers share the host operating system kernel.
- Virtual machines run with a separate guest operating system.
- Containers are lightweight and start faster.
- Virtual machines generally require more resources.

### 2. Docker Architecture
- Docker Client
- Docker Daemon
- Docker Registry (Docker Hub)

### 3. Docker Images and Containers
- Docker images are templates used to create containers.
- Containers are running instances of images.
- Downloaded and used Nginx images.

### 4. Docker Commands

Practiced important Docker commands:

- `docker version`
- `docker pull`
- `docker images`
- `docker run`
- `docker ps`
- `docker stop`
- `docker rm`
- `docker logs`
- `docker inspect`
- `docker build`

### 5. Docker Networking
- Learned Docker network types.
- Explored bridge, host, and none networks.
- Inspected container IP addresses and port mappings.

### 6. Docker Volumes and Persistent Data
- Created Docker volumes.
- Listed and inspected volumes.
- Learned how volumes help preserve application data.

### 7. Environment Variables
Practiced passing environment variables into containers.

Example:

```bash
docker run --rm \
-e APP_NAME="Student Management System" \
-e APP_ENV="Development" \
nginx:alpine sh -c 'echo $APP_NAME; echo $APP_ENV'
```

### 8. Dockerfile

Created a Dockerfile to
