# 02-state-e-backend — Gerenciamento de Estado (State) e Backends

Ciclo de vida do terraform.tfstate, backends remotos, trava de estado distribuída e operações de migração.

## 📂 Subáreas
- [`local-state/`](./local-state) — **Tecnologias:** `local backend` — Comportamento do estado em ambiente local para testes isolados e prototipação.
- [`remote-state/`](./remote-state) — **Tecnologias:** `S3, Azure Blob, GCS, Terraform Cloud` — Configuração de backend compartilhado para colaboração em equipes de engenharia.
- [`state-locking/`](./state-locking) — **Tecnologias:** `DynamoDB, Azure Blob Lease` — Mecanismos de trava de concorrência para evitar corrupção e condições de corrida no apply.
- [`import-e-migracao/`](./import-e-migracao) — **Tecnologias:** `terraform import, import block, moved` — Importação de recursos pré-existentes e refatoração de estado sem downtime.

## 📌 Fluxo Recomendado
```bash
terraform init
terraform plan
terraform apply
```
