# Proxmox Setup
# 🖥️ Proxmox Virtualization in My Home Lab

## Overview
Proxmox is the core of my home lab, allowing for **efficient virtualization, backups, and automation**.

## 🔹 Proxmox Setup
- **Two-node Proxmox cluster**: `proxn1` and `proxn2`
- **Storage**:
  - NVMe SSD for VMs
  - 2TB HDD for backups
- **Networking**:
  - Bonded NICs for high availability
  - VLAN segmentation (planned for future)

## 🔹 Automation with Ansible
I use Ansible to **automate Proxmox VM creation and maintenance**:
- Create new VMs from a template (`proxmox-vm.yml`)
- Automate backups (`backup-playbook.yml`)
- Configure network settings

## 🔹 Monitoring Proxmox with Grafana
Grafana dashboards monitor:
- CPU, RAM, and disk usage
- VM uptime
- Backup success rates

## 🔹 Future Plans
- Implement **Ceph storage** for high availability.
- Integrate **Proxmox Backup Server (PBS)** for offsite storage.
