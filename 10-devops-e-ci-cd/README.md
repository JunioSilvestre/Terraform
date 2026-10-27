# 10-devops-e-ci-cd — Pipelines de CI/CD para Terraform

Automação de workflows de validação, lint, plan especulativo e apply automatizado.

## 📂 Subáreas
- [`validacao-automatica/`](./validacao-automatica) — **Tecnologias:** `terraform fmt -check, terraform validate` — Verificação estática em pull requests para rejeitar código inválido.
- [`github-actions/`](./github-actions) — **Tecnologias:** `hashicorp/setup-terraform` — Workflows completos com comentários automáticos de plan em PRs e apply na branch main.
- [`gitlab-ci/`](./gitlab-ci) — **Tecnologias:** `gitlab-terraform template` — Integração nativa com GitLab Managed Terraform State e relatórios de infraestrutura.
- [`deployment/`](./deployment) — **Tecnologias:** `OIDC authentication (sem credenciais fixas)` — Autenticação segura via OpenID Connect com AWS e Azure nos runners.

## 📌 Fluxo Recomendado
```bash
terraform init
terraform plan
terraform apply
```
