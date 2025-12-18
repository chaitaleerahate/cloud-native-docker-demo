# Cloud Native Docker Demo

## Project Overview
This project demonstrates how to containerize a simple web application using Docker.

## Technologies Used
- Docker
- NGINX
- Linux

## Steps Performed
1. Created a simple web application
2. Built a Docker image using Dockerfile
3. Ran the container locally
4. Exposed the application via port mapping

## Outcome
The application runs successfully inside a Docker container and is accessible via browser.

## Business Use Case
This project represents a simple cloud-native web application that could be used as a lightweight service in a business environment (for example, an internal dashboard or product landing page).

## Business Lifecycle Mapping

| Stage | Description | Technology |
|------|-------------|------------|
| Requirement | Simple scalable web service | Business requirement |
| Development | Static web application | HTML |
| Build | Containerized application | Docker |
| Deployment | Application deployed to cluster | Kubernetes Deployment |
| Exposure | Service exposed to users | Kubernetes Service |
| Scaling | Increased replicas for load | Kubernetes Scaling |
| Operations | Monitoring and troubleshooting | kubectl, logs |
| Updates | Rolling updates without downtime | Kubernetes |

## Key Learnings
- Containerized applications using Docker
- Deployed and managed applications on Kubernetes
- Scaled workloads and exposed services
- Understood cloud-native application lifecycle
