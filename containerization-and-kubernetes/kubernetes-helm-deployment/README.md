# Kubernetes Helm Deployment

**Skills:** Kubernetes, Helm, Docker, Jenkins, TLS/SSL

**Overview:**  
Monorepo for a microservices application with CI/CD via Jenkins and Helm-based Kubernetes deployments.  
Each service (backend, frontend, API Gateway) has its own Dockerfile, Jenkinsfile, and Helm chart.

**Key Highlights:**  
- Jenkins Multibranch pipelines per service  
- Branch-driven CI/CD: `dev` → development cluster, `main` → production cluster  
- Semantic versioning via shared script (`scripts/version.sh`)  
- Helm charts for standardized deployments  
- Kubernetes cluster setup documented for Dev and Prod environments  
- Frontend and API Gateway exposed externally; internal services remain cluster-internal

**Repository:**  
[View on GitHub](https://github.com/rouisskhawla/kubernetes-helm-deployment)