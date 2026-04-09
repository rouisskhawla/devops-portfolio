# CI/CD Pipeline – GitLab CI

**Skills:** GitLab CI, Docker, Maven, SonarQube, Shell & Docker Executors, Multi-VM Deployment

**Overview:**  
Pipeline automates building, testing, SonarQube analysis, Docker image creation, and deployment to a staging VM using GitLab CI/CD.

**Key Highlights:**  
- `.gitlab-ci.yml` defines stages: test, sonarqube, package, image-build, deploy-staging  
- Uses Docker and Shell executor runners on Ubuntu WSL  
- Secure GitLab CI/CD variables for credentials and VM access  
- Staging VM deployment via SSH and Docker Compose  

**Original Repository:**  
[View on GitHub](https://github.com/rouisskhawla/devops-ci-cd-pipeline-gitlab-ci)