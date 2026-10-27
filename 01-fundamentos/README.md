# 01-fundamentos — Fundamentos de Terraform e HCL

Conceitos essenciais de Infraestrutura como Código (IaC), sintaxe HashiCorp Configuration Language (HCL), providers, recursos e variáveis.

## 📂 Subáreas
- [`sintaxe-hcl/`](./sintaxe-hcl) — **Tecnologias:** `terraform, hcl` — Blocos fundamentais, tipos primitivos e complexos, expressões ternárias, loops (for_each, count) e funções nativas.
- [`providers/`](./providers) — **Tecnologias:** `hashicorp/aws, hashicorp/azurerm, hashicorp/local` — Configuração de provedores, versionamento de providers e alias para múltiplas regiões/contas.
- [`resources-e-data-sources/`](./resources-e-data-sources) — **Tecnologias:** `resource, data` — Declaração de estado desejado de recursos e consulta de recursos externos via Data Sources.
- [`variables-e-outputs/`](./variables-e-outputs) — **Tecnologias:** `variable, output, terraform.tfvars` — Parametrização dinâmica com validações personalizadas e exportação de valores essenciais.

## 📌 Fluxo Recomendado
```bash
terraform init
terraform plan
terraform apply
```
