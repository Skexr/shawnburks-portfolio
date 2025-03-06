# monitoring
# 📊 Monitoring & Security in My Home Lab

## Overview
I use **Grafana, Prometheus, and Elasticsearch** to monitor system performance and security events.

## 🔹 Monitoring Setup
- **Grafana Dashboards**: Tracks Proxmox usage, AI server activity, and game server uptime.
- **Prometheus Exporters**:
  - Node Exporter (system metrics)
  - Blackbox Exporter (ping external services)
  - Proxmox Exporter (VM stats)
- **Elasticsearch & Kibana**: Logs and visualizes system events.

## 🔹 Security Setup
- **Fail2Ban Logs**: Protects SSH and game servers from brute-force attacks.
- **AI-Based Alerts**: Uses Ansible + Elasticsearch for log analysis.
- **Automated Backups**: Ensures configuration safety for all VMs.

## 🔹 Future Plans
- Set up **real-time log monitoring** with Kibana.
- Implement **AI-based anomaly detection** for network traffic.
