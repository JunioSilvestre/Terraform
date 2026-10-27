# 11-testes-e-qualidade — Testes, Linter e Segurança Estática de IaC

Ferramentas para garantir conformidade de segurança, padronização e testes automatizados.

## 📂 Subáreas
- [`fmt-e-validate/`](./fmt-e-validate) — **Tecnologias:** `terraform fmt, terraform validate` — Padronização de formatação e verificação de consistência interna do código.
- [`tflint/`](./tflint) — **Tecnologias:** `TFLint, tflint-ruleset-aws` — Detecção de erros específicos de providers e violações de boas práticas.
- [`checkov/`](./checkov) — **Tecnologias:** `Checkov, Trivy, tfsec` — Varredura de segurança estática para identificar vulnerabilidades e má configurações de compliance.
- [`terraform-test/`](./terraform-test) — **Tecnologias:** `terraform test (HCL native test framework)` — Testes nativos de assertions para validar inputs, outputs e comportamentos.

## 📌 Fluxo Recomendado
```bash
terraform init
terraform plan
terraform apply
```
