# 04-aws — Infraestrutura como Código na AWS

Implementação prática de recursos essenciais da Amazon Web Services com foco em segurança e alta disponibilidade.

## 📂 Subáreas
- [`compute/`](./compute) — **Tecnologias:** `aws_instance, aws_autoscaling_group, aws_launch_template` — Instâncias EC2, grupos de auto-scaling e modelos de inicialização.
- [`storage/`](./storage) — **Tecnologias:** `aws_s3_bucket, aws_ebs_volume, aws_efs_file_system` — Armazenamento em objetos S3 com versionamento/criptografia e volumes de blocos.
- [`networking/`](./networking) — **Tecnologias:** `aws_vpc, aws_subnet, aws_nat_gateway, aws_route_table` — VPCs multi-AZ, subnets públicas/privadas e gateways de internet/NAT.
- [`iam-e-seguranca/`](./iam-e-seguranca) — **Tecnologias:** `aws_iam_role, aws_iam_policy, aws_security_group` — Princípio do menor privilégio, IAM roles para instâncias e Security Groups rigorosos.

## 📌 Fluxo Recomendado
```bash
terraform init
terraform plan
terraform apply
```
