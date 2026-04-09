# Multi-Environment CI/CD: Minikube & Kubernetes Cluster

**Skills:** Kubernetes, Minikube, Jenkins, Docker, Spring Boot

**Overview:**  
A CI/CD pipeline for a Spring Boot application that deploys automatically to **Minikube** (local dev) or a **remote Kubernetes cluster** (production) based on GitHub webhook events.

**Key Highlights:**  
- Single Jenkins pipeline manages both environments  
- Minikube: triggered on `main` branch pushes for development/testing  
- Kubernetes cluster: triggered on Git tag pushes for production  
- Automated Docker image versioning and tagging  
- Helm-based deployments for standardization  
- GitHub webhook integration using ngrok for private Jenkins VM  
- Environment-specific manifests in `minikube-deploy/` and `cluster-deploy/`

**Repository:**  
[View on GitHub](https://github.com/rouisskhawla/k8s-minikube-vs-cluster)