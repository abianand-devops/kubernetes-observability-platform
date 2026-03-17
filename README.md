\# Kubernetes Observability Platform



This project demonstrates a production-style monitoring and incident response system for Kubernetes.



\## Stack



\- Amazon EKS

\- Prometheus

\- Grafana

\- Alertmanager

\- Webhook incident automation



\## Architecture



Application → Prometheus → Alertmanager → Webhook → Incident system



\## Features



\- Kubernetes cluster monitoring

\- Custom Prometheus alerts

\- Grafana dashboards

\- Incident webhook simulation

\- Environment-based alerting (dev / prod)



\## Alerts Implemented



\- High CPU usage

\- Test immediate alert

\- Node CPU saturation



\## Demo Workflow



1\. Application generates high CPU load

2\. Prometheus detects anomaly

3\. Alert rule triggers

4\. Alertmanager processes alert

5\. Webhook receives alert payload

6\. Incident system can create ticket

