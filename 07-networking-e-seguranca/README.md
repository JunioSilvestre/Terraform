# 07-networking-e-seguranca — Arquitetura de Redes e Segurança em IaC

Topologias seguras, segmentação de tráfego, inspeção de borda e políticas de acesso centralizadas.

## 📂 Subáreas
- [`vpc-e-vnet/`](./vpc-e-vnet) — **Tecnologias:** `CIDR planning, Peering, Transit Gateway` — Design de topologias de rede corporativa hub-and-spoke e roteamento global.
- [`subnets-e-routing/`](./subnets-e-routing) — **Tecnologias:** `Public, Private, Database subnets` — Isolamento de camadas de aplicação, bancos de dados e DMZ.
- [`firewalls/`](./firewalls) — **Tecnologias:** `WAF, Security Groups, NSGs, Cloud Armor` — Controle de tráfego de entrada e saída por regras de borda.
- [`iam-e-politicas/`](./iam-e-politicas) — **Tecnologias:** `SCP, Guardrails, IAM Policies` — Aplicação de políticas preventivas e permissões baseadas em funções.

## 📌 Fluxo Recomendado
```bash
terraform init
terraform plan
terraform apply
```
