# 💾 Backup Strategy

## Current Backup Plan
- **Proxmox Backup Server (PBS)** handles VM snapshots.
- **Game server data** is backed up nightly.
- **Critical configuration files** are stored in Git.

## Storage Devices
| Type    | Location  | Capacity  |
|---------|----------|-----------|
| RAID 5  | proxn1   | 5 SAS Drives |
| NVMe    | proxn2   | 1TB SSD   |
| HDD     | proxn2   | 2TB Backup |
