# naming-e-tags

> Tags obrigatórias: Environment, Project, Owner, ManagedBy=Terraform

## 🛠️ Tecnologias & Comandos
- `terraform, hcl`

## 📋 Boas Práticas & Estrutura
- Mantenha a separação padrão de arquivos:
  - `main.tf`: Declaração dos recursos principais.
  - `variables.tf`: Definição de variáveis com tipos e descrições.
  - `outputs.tf`: Exportação de atributos úteis.
  - `versions.tf`: Versão mínima do Terraform e providers requeridos.
- Sempre execute `terraform fmt` e `terraform validate` antes de submeter alterações.
- Nunca versione arquivos `.tfstate` ou senhas em texto puro.
