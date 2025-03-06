# 🌐 Networking Overview

## Current Network Setup
The homelab network is designed to support **virtualization, game servers, and AI workloads**.

### **Network Infrastructure**
- **Router**: Asus RT-AXE7800 (Google Fiber in Bridge Mode)
- **Proxmox Hosts**: `proxn1`, `proxn2` (Bonded NICs)
- **DNS Configuration**: Cloudflare DDNS (Planned: Pi-hole)
- **VPN Access**: WireGuard for secure remote access
- **Firewall Rules**: UFW + IPTables

## Future Plans:
- **Implement VLAN segmentation** for improved security.
- **Internal DNS setup** with **Pi-hole or Unbound**.
