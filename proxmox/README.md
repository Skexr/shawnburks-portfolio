# 🖥️ Proxmox Virtualization

## Overview
Proxmox is the **primary virtualization platform** used in the homelab to manage VMs and LXC containers.

## Cluster Configuration:
| Node   | Role                     | Storage Setup                      |
|--------|--------------------------|-----------------------------------|
| `proxn1` | Primary compute & game servers | RAID 5 (SAS drives, PERC H710) |
| `proxn2` | AI workloads & backups  | NVMe SSDs + 2TB HDD for PBS |

## Features:
- **High Availability:** Two-node cluster for redundancy
- **Backup Strategy:** Daily backups using **Proxmox Backup Server (PBS)**
- **Monitoring:** Integrated with **Grafana & Prometheus**
