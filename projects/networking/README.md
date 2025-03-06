# Networking Configurations
# 🌐 Networking & Security in My Home Lab

## Overview
Networking is a critical part of my home lab, ensuring **secure remote access, high performance, and automation**.

## 🔹 Network Infrastructure
| Device        | Model             | Function |
|--------------|------------------|----------|
| Router       | Asus RT-AXE7800  | Core router with DDNS |
| Firewall     | iptables/UFW     | Security filtering |
| VPN Server   | WireGuard        | Secure remote access |
| Switch       | Managed L2       | VLAN segmentation (future) |

## 🔹 Security Hardening
- **Fail2Ban** – Automated IP banning for failed SSH attempts.
- **Cloudflare DDNS** – Dynamic DNS for easy remote access.
- **Firewall Rules** – Strict port control for home lab security.

## 🔹 Future Plans
- Implement **VLAN segmentation** once new hardware is available.
- Automate firewall rules via **Ansible**.
