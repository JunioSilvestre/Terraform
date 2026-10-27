# 08-containers-e-kubernetes — Containers, Registries e Kubernetes

Criação de clusters gerenciados (EKS, AKS, GKE) e provisionamento de workloads via provider Kubernetes/Helm.

## 📂 Subáreas
- [`docker/`](./docker) — **Tecnologias:** `kreuzwerker/docker` — Gerenciamento de containers locais, imagens e redes via IaC.
- [`clusters/`](./clusters) — **Tecnologias:** `aws_eks_cluster, azurerm_kubernetes_cluster` — Provisionamento de clusters Kubernetes gerenciados e node pools.
- [`kubernetes/`](./kubernetes) — **Tecnologias:** `hashicorp/kubernetes, hashicorp/helm` — Deployment de charts Helm, namespaces, ingress controllers e secrets.

## 📌 Fluxo Recomendado
```bash
terraform init
terraform plan
terraform apply
```
