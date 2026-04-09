# Monitoring Stack: Grafana, Prometheus & k6

**Skills:** Prometheus, Grafana, k6, InfluxDB, Docker, Observability

**Overview:**  
A complete monitoring and load testing environment with distributed setup across two VMs.  
Prometheus collects system metrics, Grafana visualizes them, and k6 generates load tests with results stored in InfluxDB.

**Key Highlights:**  
- System metrics collection using Node Exporter  
- Real-time monitoring with Prometheus and Grafana dashboards  
- Load and stress testing with k6 (multiple scenarios: baseline, stress, spike)  
- Metrics storage and analysis using InfluxDB  
- Multi-VM architecture separating application and monitoring stack  
- Docker Compose used for all services deployment  

**Repository:**  
[View on GitHub](https://github.com/rouisskhawla/monitoring-grafana-prometheus-k6)