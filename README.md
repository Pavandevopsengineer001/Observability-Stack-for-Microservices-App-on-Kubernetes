# Observability-Stack-for-Microservices-App-on-Kubernetes
Demonstrates observability for a sample microservices application deployed in Kubernetes, using Prometheus for metrics, Grafana for dashboards, and custom instrumentation with exporters.


📦 Tech Stack:

Kubernetes

Node.js or Python microservices

Prometheus (scraping app metrics)

Grafana (app-specific dashboards)

Helm or raw manifests

🧩 Features:

Deploys a sample microservice with Prometheus /metrics endpoint

Uses prometheus-operator or ServiceMonitor for scraping

Custom Grafana dashboards for application metrics (e.g., HTTP latency, error rates)

GitHub Actions for CI/CD to deploy app + update dashboards
