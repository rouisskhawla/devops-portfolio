# Redis & Vault Integration (Spring Boot)

**Skills:** HashiCorp Vault, Redis, TLS/SSL, Spring Boot, Secrets Management

**Overview:**  
Spring Boot application integrated with HashiCorp Vault and Redis, where Vault securely manages credentials and TLS certificates.  
The application retrieves secrets at runtime using AppRole authentication and connects to Redis over TLS.

**Key Highlights:**  
- Centralized secrets management using HashiCorp Vault  
- Secure Redis communication with TLS certificates  
- AppRole authentication for dynamic secret access  
- Auto-unseal Vault setup using systemd and scripting  
- Integration of Vault secrets into Spring Boot at runtime  
- Local development setup using Java KeyStore for certificates  

**Repository:**  
[View on GitHub](https://github.com/rouisskhawla/redis-vault-spring-boot)