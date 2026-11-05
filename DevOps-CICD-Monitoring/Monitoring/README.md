\# DevOps CI/CD Monitoring



\## 1. Overview



This project demonstrates application monitoring using Prometheus, Grafana, and cAdvisor.



\## 2. Tools Used



\- Docker

\- Docker Compose

\- Prometheus

\- Grafana

\- cAdvisor



\## 3. Monitoring Architecture



\- \*\*Prometheus:\*\* Collects monitoring metrics.

\- \*\*cAdvisor:\*\* Collects Docker container metrics.

\- \*\*Grafana:\*\* Visualizes metrics using dashboards.



\## 4. Services and Ports



| Service | Port |

|---|---|

| Prometheus | 9090 |

| Grafana | 3000 |

| cAdvisor | 8081 |



\## 5. Setup Instructions



Run the following command inside the Monitoring directory:



```bash

docker compose up -d

```



Check running containers:



```bash

docker ps

```



\## 6. Access Monitoring Tools



\- Prometheus: http://localhost:9090

\- Prometheus Targets: http://localhost:9090/targets

\- Grafana: http://localhost:3000

\- cAdvisor: http://localhost:8081



\## 7. Grafana Dashboard



Created a monitoring dashboard to visualize:



\- Docker Container CPU Usage

\- Docker Container Memory Usage



Prometheus is configured as the Grafana data source.



\## 8. Learning Outcomes



\- Learned how to configure Prometheus.

\- Learned how to monitor Docker containers using cAdvisor.

\- Connected Prometheus with Grafana.

\- Created monitoring dashboards.

\- Practiced Docker Compose.

