# Docker & Containerization

## 1. Overview

This module focuses on learning Docker and containerization concepts and deploying a web application using Docker and Docker Compose.

## 2. Learning Objectives

- Understand containers and virtual machines.
- Learn Docker architecture, images, and containers.
- Practice essential Docker commands.
- Understand Docker networking and volumes.
- Learn environment variables and persistent data.
- Create Dockerfiles.
- Manage applications using Docker Compose.
- Deploy a containerized web application.

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
- `docker pull`
- `docker images`
- `docker run`
- `docker ps`
- `docker stop`
- `docker logs`
- `docker inspect`
- `docker build`

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
Created a Dockerfile using the Nginx Alpine image to build a custom Docker image.

### Docker Compose
Created a `docker-compose.yml` file to build and run the application.

## 5. Practical Project – Student Management System

### Project Description

Created a simple Student Management web application and containerized it using Docker and Nginx.

### Application Features

- Displays Student Management System heading.
- Displays project information.
- Shows application running status.
- Displays student name.

### Project Structure

```text
Docker-Containerization/
├── README.md
├── student-project/
│   ├── index.html
│   ├── Dockerfile
│   └── docker-compose.yml
└── Screenshots/
```

### Deployment Workflow

Source Code → Dockerfile → Docker Image → Docker Container → Docker Compose → Running Application

### Application Testing

```bash
docker compose up -d --build
docker compose ps
curl http://localhost:8081
```

Successfully tested the application and received the expected HTML response.

**Application Port:** `8081`

## 6. Screenshots

Practical screenshots are available in the [Screenshots folder
