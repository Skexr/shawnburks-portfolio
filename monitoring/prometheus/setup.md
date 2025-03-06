# 📡 Prometheus Setup

## Overview
Prometheus is used for **real-time metrics collection** from various homelab services.

## Configuration:
- **Prometheus UI**: `http://your-ip:9090`
- **Targets Monitored:** Proxmox, Game Servers, AI Server
- **Alerting System:** Integrated with Grafana AlertManager

## Installation:
```bash
sudo apt install -y prometheus
sudo systemctl enable --now prometheus

