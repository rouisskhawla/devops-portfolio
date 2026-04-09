# Microservices DevOps Monorepo

**Skills:** Docker, CI/CD, GitHub Actions, Spring Boot, Angular, TLS/SSL

**Overview:**  
A single repository consolidating backend services, frontend, and CI/CD workflows for a microservices architecture.  
Each service has its own Dockerfile, Docker Compose setup, and dedicated pipeline triggered only on relevant changes.

**Key Highlights:**  
- Microservices architecture with Spring Boot and Angular  
- All services deployable as Docker containers on one VM  
- CI/CD pipelines per service with GitHub Actions  
- Shared Docker network for service communication  
- Local HTTPS with Nginx and self-signed certificates

**Original Multi-Repo Project:**  
[View on GitHub](https://github.com/rouisskhawla/microservices-devops-monorepo)