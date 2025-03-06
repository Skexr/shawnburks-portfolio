# 🛠 VLAN Configuration (Future Plan)

## Overview
Currently, VLANs are **not implemented**, but plans are in place to segment network traffic.

## Planned VLAN Setup:
| VLAN ID | Purpose            | Devices Assigned |
|---------|-------------------|-----------------|
| 10      | Management        | Proxmox, Routers |
| 20      | Game Servers      | `wings1`, `wings2` |
| 30      | AI & Automation   | `Jarvis` (AI Server) |

## Benefits:
- **Improved Security**: Prevent unnecessary cross-traffic.
- **Better Traffic Isolation**: Reduces network congestion.
- **Easier Access Control**: Different security policies per VLAN.
