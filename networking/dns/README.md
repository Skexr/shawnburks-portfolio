# 🌍 DNS Configuration

## Overview
DNS is managed via **Cloudflare DDNS** for public-facing services, while internal resolution is currently **handled manually**.

### **Current DNS Setup**
- **Public Domain**: `dystopia.games` (Cloudflare-managed)
- **DDNS Service**: Cloudflare API for dynamic IP updates
- **Internal Resolution**: Currently `/etc/hosts` (Planned: Pi-hole or Unbound)

### **Future Enhancements**
- **Deploy Pi-hole or Unbound** for **internal hostname resolution**.
- **Split-Horizon DNS**: Separate **internal and external** DNS queries.
