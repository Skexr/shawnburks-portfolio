## 🏗️ Home Lab Overview
### **Infrastructure & Hardware**
- **Proxmox Cluster** (`proxn1`, `proxn2`, `proxn2`) – Virtualization and backups
- **Dell PowerEdge R710** – Game servers, AI workloads, monitoring
- **HP Z1 G5 Workstation (`Jarvis`)** – Dedicated AI server GPU PT
- **Dell PowerEdge R730xd** - Game servers, AI workloads, monitoring, GPU PT
- **Networking**
  - Asus RT-AXE7800 Router (Google Fiber in Bridge Mode)
  - VLAN segmentation for isolation
  - Nginx Proxy Manager for reverse proxy
  - Cloudflare DDNS for public access
- **Storage Architecture**
  - NVMe SSDs for high-performance VMs
  - 2TB HDD for Proxmox Backup Server (PBS)
