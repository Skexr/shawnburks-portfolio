# 📊 Grafana Setup

## Overview
Grafana is used for **visualizing homelab system metrics** collected from **Prometheus** and **PostgreSQL**.

## Configuration:
- **Grafana UI**: `http://your-ip:3000`
- **Reverse Proxy:** Nginx Proxy Manager
- **Authentication:** User-based access control

## Installation:
```bash
sudo apt install -y grafana
sudo systemctl enable --now grafana-server
