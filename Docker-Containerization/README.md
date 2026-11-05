# Docker & Containerization

## 1. Overview

This module focuses on learning Docker and containerization concepts and deploying a web application using Docker.

## 2. Learning Objectives

- Understand containers and virtual machines.
- Learn Docker architecture, images, and containers.
- Practice Docker commands.
- Understand Docker networking and volumes.
- Learn environment variables and persistent data.
- Create and optimize Dockerfiles.
- Manage applications using Docker Compose.
- Deploy a web application using Docker.

## 3. Technologies Used

- Docker
- Docker Compose
- Nginx
- HTML
- Linux
- Docker Hub

## 4. Topics Covered

### Docker Fundamentals
- Containers vs Virtual Machines
- Docker Architecture
- Docker Images
- Docker Containers
- Docker Registry

### Docker Commands
- docker pull
- docker images
- docker run
- docker ps
- docker stop
- docker logs
- docker inspect
- docker build

### Docker Networking
- Bridge Network
- Host Network
- None Network
- Port Mapping
- Container IP Address

### Docker Volumes
- Creating Docker Volumes
- Listing Volumes
- Inspecting Volumes
- Persistent Data

### Environment Variables
Practiced passing environment variables into containers using the `-e` option.

### Dockerfile
Created a Dockerfile using the Nginx Alpine image.

### Docker Compose
Created a Docker Compose YAML file to build and run the application.

## 5. Practical Project – Student Management System

### Project Description

Created a simple Student Management web application and containerized it using Docker and Nginx.

### Application Details

- Displays Student Management System heading.
- Displays project information.
- Shows application running status.
- Displays student name.

### Project Structure

```text
student-project/
├── index.html
├── Dockerfile
└── docker-compose.yml
```

### Deployment Workflow

Source Code → Dockerfile → Docker Image → Container → Docker Compose → Running Application

### Application Testing

```bash
curl http://localhost:8081
```

Successfully tested the application and received the HTML content.

## 6. Screenshots

Practical screenshots are available in the `Screenshots` folder.

- Docker Version
- Docker Image Download
- Docker Images
- Running Containers
- Nginx Website Test
- Docker Networking
- Docker Volumes
- Docker Image Build
- Docker Compose
- Student Website Test
- Environment Variables

## 7. Learning Outcomes

After completing this module, I gained practical knowledge of:

- Docker fundamentals and architecture.
- Building and managing Docker images.
- Running and managing containers.
- Docker networking and volumes.
- Environment variable configuration.
- Creating Dockerfiles.
- Using Docker Compose.
- Deploying a containerized web application.

## 8. Conclusion

Successfully completed the Docker and Containerization module by building and deploying a Student Management web application using Docker, Nginx, and Docker Compose.

This practical experience helped me understand the fundamentals of containerization and application deployment as part of my DevOps learning journey.
