# 🖥️ Proxmox Virtualization

## Overview
The Proxmox cluster consists of two nodes running a mix of game servers, AI workloads, and infrastructure services.

### **Cluster Setup**
| Node   | Storage Setup                          | Role                   |
|--------|----------------------------------------|------------------------|
| proxn1 | 5-disk RAID 5 (SAS, PERC H710)         | Virtualization         |
| proxn2 | NVMe SSDs RTX 3050 6gb GPU passthroug  | High-performance VMs   |
| proxn3 | 7-disk Raid 6 (SAS, PERC H730)         | Virtualization         |

### **Automations & Backups**
- **Ansible Playbooks** automate provisioning.
- **Proxmox Backup Server (PBS)** stores VM snapshots.
- **VMs are backed up daily** to prevent data loss.
