# GitOps-Deploy – Automated CD & Observability Pipeline

Kubernetes manifests and ArgoCD configs for GitOps delivery with Prometheus + Grafana observability.

Built and maintained by **Kaushal Raithatha**.

## Features
- ArgoCD Application manifests for auto-sync delivery
- Kubernetes Deployment, Service, HPA manifests
- Prometheus metric scraping and Grafana dashboards

## Tech Stack
ArgoCD · Kubernetes · Helm · Prometheus · Grafana

## Deploy
```bash
kubectl apply -f argocd/application.yaml
kubectl apply -f k8s/
```

## Author
**Kaushal Raithatha** – [GitHub](https://github.com/Kausha07)
