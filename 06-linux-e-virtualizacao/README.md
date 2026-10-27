# 06-linux-e-virtualizacao — Linux, Homelab e Virtualização Local

IaC aplicado a ambientes on-premises, Proxmox, VMware e máquinas virtuais locais.

## 📂 Subáreas
- [`maquinas-virtuais/`](./maquinas-virtuais) — **Tecnologias:** `Telmate/proxmox, VMware/vsphere` — Provisionamento automatizado de VMs Linux a partir de templates Cloud-Init.
- [`redes/`](./redes) — **Tecnologias:** `Bridges, VLANs, vSwitch` — Configuração de interfaces e redes virtuais para hosts locais.
- [`storage/`](./storage) — **Tecnologias:** `ZFS pools, LVM, NFS datastores` — Alocação e particionamento de volumes para hypervisors.
- [`homelab/`](./homelab) — **Tecnologias:** `Docker, VMs de laboratório` — Infraestrutura reproduzível para laboratórios caseiros e testes de SRE.

## 📌 Fluxo Recomendado
```bash
terraform init
terraform plan
terraform apply
```
