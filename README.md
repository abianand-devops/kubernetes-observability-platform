\# Kubernetes Observability Platform

This project demonstrates a production-grade Kubernetes monitoring and alerting system using Grafana and Prometheus on AWS EKS.

\---

\## 🔧 Tech Stack



\- AWS EKS (Kubernetes)

\- Prometheus (Monitoring)

\- Grafana (Visualization)

\- Alertmanager (Alert Routing)

\- Kubernetes (Workloads \& Metrics)

\---



\## 📊 Grafana Dashboards



This project includes 4 professional dashboards designed for real-world monitoring:



\### 1. System Overview

\- Cluster CPU \& Memory usage

\- Running Pods \& Node count

\- Resource utilization trends



\### 2. Application Performance

\- Traffic (Request rate)

\- Error trends

\- Latency (simulated for demo)

\- Pod-level performance



\### 3. Infrastructure Metrics

\- Node CPU \& Memory usage

\- Network traffic (Ingress/Egress)

\- Node-level performance comparison



\### 4. Alerts \& Health

\- Active / Pending / Resolved alerts

\- Alert trends over time

\- Alert details table



\---



\## 📸 Dashboard Screenshots



\### System Overview

&#x20;





\### Application Performance

&#x20;





\### Infrastructure Metrics

&#x20;





\### Alerts \& Health

&#x20;





\---





\## 🚨 Alerting



\- High CPU usage alert implemented using PrometheusRule

\- Alertmanager webhook integration configured

\- Real-time alert triggering tested

\- Alerts successfully delivered to webhook service



\---



\## 📦 Deliverables



\- Grafana Dashboard JSON files (import-ready)

\- Prometheus alert rules

\- Kubernetes manifests

\- Alertmanager webhook configuration

\- Complete monitoring setup



\---



\## 📁 Project Structure



alerts/

dashboards/

screenshots/

README.md



\---



\## 💼 Use Case



This project simulates a real-world DevOps monitoring setup suitable for:



\- Production Kubernetes cluster observability

\- Performance monitoring \& optimization

\- Incident detection \& alerting

\- Freelance and portfolio demonstration



\---



\## 🚀 How to Use



1\. Deploy Kubernetes cluster (EKS)

2\. Install Prometheus \& Grafana

3\. Import dashboard JSON files

4\. Apply alert rules

5\. Monitor cluster and visualize metrics



\---



\## 📌 Note



Some application-level metrics are simulated using system metrics for demonstration purposes.



\---



\## 👨‍💻 Author



DevOps Engineer | Kubernetes | Monitoring | Observability



