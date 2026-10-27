# 09-ambientes — Estratégia de Múltiplos Ambientes

Padrões de segregação de ambientes (Dev, Staging, Prod) via workspaces ou diretórios isolados.

## 📂 Subáreas
- [`lab/`](./lab) — **Tecnologias:** `terraform, hcl` — Ambiente efêmero para experimentos rápidos e PoCs sem impacto.
- [`development/`](./development) — **Tecnologias:** `terraform, hcl` — Ambiente de desenvolvimento com instâncias de baixo custo.
- [`staging/`](./staging) — **Tecnologias:** `terraform, hcl` — Ambiente espelho de homologação e validação pré-produção.
- [`production/`](./production) — **Tecnologias:** `terraform, hcl` — Ambiente crítico com alta disponibilidade, backups e travas estritas.

## 📌 Fluxo Recomendado
```bash
terraform init
terraform plan
terraform apply
```
