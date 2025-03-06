# ⚙️ Proxmox Setup & Installation

## Installation Steps
1. Download the latest **Proxmox VE ISO**.
2. Install Proxmox on `proxn1` & `proxn2` with RAID/NVMe configurations.
3. Configure storage:
   ```bash
   pvesm add nfs backups --server 192.168.50.20 --export /mnt/nfs-proxmox-backups
   pvecm create homelab-cluster
   sed -i 's/^deb/#deb/g' /etc/apt/sources.list.d/pve-enterprise.list
