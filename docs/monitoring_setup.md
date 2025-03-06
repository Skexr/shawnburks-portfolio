# 📊 Monitoring Setup

## Stack Overview
The home lab uses a mix of open-source monitoring tools.

### **Current Monitoring Tools**
- **Grafana** (Dashboards)
- **Prometheus** (Metrics Collection)
- **Elasticsearch + Kibana** (Logging)

### **Key Metrics Monitored**
| Component      | Monitored Metrics           |
|---------------|----------------------------|
| Proxmox       | CPU, Memory, Disk Usage    |
| Game Servers  | Player Count, Performance |
| AI Server     | Request Logs, Failures     |
