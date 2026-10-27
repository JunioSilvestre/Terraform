# 12-arquitetura-e-boas-praticas — Arquitetura e Boas Práticas Corporativas

Padrões de nomenclatura, tagueamento mandatório, estimativa de custos e resiliência.

## 📂 Subáreas
- [`convencoes/`](./convencoes) — **Tecnologias:** `terraform, hcl` — Estrutura de arquivos: main.tf, variables.tf, outputs.tf, versions.tf
- [`naming-e-tags/`](./naming-e-tags) — **Tecnologias:** `terraform, hcl` — Tags obrigatórias: Environment, Project, Owner, ManagedBy=Terraform
- [`custos/`](./custos) — **Tecnologias:** `terraform, hcl` — Infracost, estimativas prévias de custos antes de aplicar modificações
- [`alta-disponibilidade/`](./alta-disponibilidade) — **Tecnologias:** `terraform, hcl` — Multi-AZ, failover, balanceadores de carga e zonas de disponibilidade

## 📌 Fluxo Recomendado
```bash
terraform init
terraform plan
terraform apply
```
