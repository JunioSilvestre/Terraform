# 03-modulos — Módulos Reutilizáveis e Componentização

Arquitetura modular em Terraform, padrões de encapsulamento, versionamento semântico e publicação.

## 📂 Subáreas
- [`modulos-locais/`](./modulos-locais) — **Tecnologias:** `source = ./modules/...` — Criação de módulos internos para isolar blocos de infraestrutura dentro do próprio repositório.
- [`modulos-reutilizaveis/`](./modulos-reutilizaveis) — **Tecnologias:** `Inputs, Outputs, README.md` — Padrão ouro de construção de módulos genéricos, testáveis e independentes.
- [`registry/`](./registry) — **Tecnologias:** `Terraform Registry` — Consumo e publicação de módulos públicos e privados da comunidade.
- [`versionamento/`](./versionamento) — **Tecnologias:** `git tags, ref = v1.0.0` — Fixação de versões estritas de módulos em ambientes de produção.

## 📌 Fluxo Recomendado
```bash
terraform init
terraform plan
terraform apply
```
