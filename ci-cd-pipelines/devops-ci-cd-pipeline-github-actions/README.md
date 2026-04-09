# CI/CD Pipeline – GitHub Actions

**Skills:** GitHub Actions, Docker, SonarQube, Multi-Environment Deployment, Semantic Versioning

**Overview:**  
CI/CD workflow for a Spring Boot application with automated testing, code quality analysis, Docker containerization, and deployment to staging and production environments.

**Key Highlights:**  
- Workflows: `ci.yml`, `staging.yml`, `production.yml`  
- Automatic snapshot and release versioning  
- Staging VM receives snapshots, production VM receives releases  
- Self-hosted runner on Ubuntu WSL  
- Secure secrets stored in GitHub

**Original Repository:**  
[View on GitHub](https://github.com/rouisskhawla/devops-ci-cd-pipeline-github-actions)