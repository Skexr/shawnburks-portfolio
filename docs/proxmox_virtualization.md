# 🖥️ Proxmox Virtualization

## Overview
The Proxmox cluster consists of two nodes running a mix of game servers, AI workloads, and infrastructure services.

### **Cluster Setup**
| Node   | Storage Setup                        | Role                   |
|--------|-------------------------------------|------------------------|
| proxn1 | 5-disk RAID 5 (SAS, PERC H710)    | Virtualization         |
| proxn2 | NVMe SSDs                          | High-performance VMs   |

### **Automations & Backups**
- **Ansible Playbooks** automate provisioning.
- **Proxmox Backup Server (PBS)** stores VM snapshots.
- **VMs are backed up daily** to prevent data loss.
