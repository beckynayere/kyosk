# kyosk

# Spring Boot Application with CI/CD and Kubernetes Deployment

## Overview
A simple Spring Boot REST API deployed using Docker, CI/CD pipeline (GitHub Actions), and Minikube.

## Steps to Build and Run

### Prerequisites:
- Docker
- Minikube
- Kubernetes CLI (`kubectl`)
- Maven
- GitHub Actions enabled

### Build and Run Locally with Docker
1. Build the Docker image:
   ```bash
   docker build -t your-dockerhub-username/springboot-demo:latest .

