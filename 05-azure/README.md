# 05-azure — Infraestrutura como Código na Microsoft Azure

Provisionamento corporativo no Microsoft Azure utilizando o provider azurerm.

## 📂 Subáreas
- [`resource-groups/`](./resource-groups) — **Tecnologias:** `azurerm_resource_group` — Organização lógica, ciclo de vida e delimitação de governança de recursos.
- [`compute/`](./compute) — **Tecnologias:** `azurerm_linux_virtual_machine, vmss` — Máquinas virtuais Linux, scale sets e provisionamento com cloud-init.
- [`networking/`](./networking) — **Tecnologias:** `azurerm_virtual_network, azurerm_subnet, azurerm_nsg` — VNet, subnets segmentadas e Network Security Groups (NSGs).
- [`identity-e-rbac/`](./identity-e-rbac) — **Tecnologias:** `azurerm_role_assignment, Managed Identities` — Identidades gerenciadas para autenticação segura entre serviços Azure.

## 📌 Fluxo Recomendado
```bash
terraform init
terraform plan
terraform apply
```
