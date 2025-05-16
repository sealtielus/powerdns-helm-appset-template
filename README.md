# PowerDNS Helm ApplicationSet Template

This is a minimal GitOps-ready Helm chart and Argo CD ApplicationSet configuration for deploying [PowerDNS](https://www.powerdns.com/) in a Kubernetes environment.

## 🧱 Structure

- `charts/powerdns/`: Basic PowerDNS Helm chart
- `argocd/application-set.yaml`: ApplicationSet for deploying to a namespace via Argo CD

## 🚀 Usage

1. Fork this repo
2. Adjust values in `values.yaml` and `application-set.yaml`
3. Apply `application-set.yaml` to your Argo CD instance
4. Watch it deploy PowerDNS

## 🛠 Requirements

- Argo CD with ApplicationSet controller
- Kubernetes cluster
