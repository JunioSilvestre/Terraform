# iam-e-seguranca

> Princípio do menor privilégio, IAM roles para instâncias e Security Groups rigorosos.

## 🛠️ Tecnologias & Comandos
- `aws_iam_role, aws_iam_policy, aws_security_group`

## 📋 Boas Práticas & Estrutura
- Mantenha a separação padrão de arquivos:
  - `main.tf`: Declaração dos recursos principais.
  - `variables.tf`: Definição de variáveis com tipos e descrições.
  - `outputs.tf`: Exportação de atributos úteis.
  - `versions.tf`: Versão mínima do Terraform e providers requeridos.
- Sempre execute `terraform fmt` e `terraform validate` antes de submeter alterações.
- Nunca versione arquivos `.tfstate` ou senhas em texto puro.
