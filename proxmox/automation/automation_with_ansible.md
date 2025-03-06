# 🤖 Automating Proxmox with Ansible

## Overview
Proxmox deployments are automated with **Ansible Playbooks** to simplify VM creation, backups, and system updates.

## Current Ansible Playbooks:
- **VM Creation & Configuration**
- **Daily Backup Scheduling**
- **Proxmox System Updates**

## Example Ansible Task:
```yaml
- name: Create a new Proxmox VM
  proxmox_kvm:
    api_host: "{{ proxmox_host }}"
    node: "{{ proxmox_node }}"
    vmid: 105
    name: "homelab-vm"
    memory: 4096
    cores: 2
    storage: "local-lvm"
```

Future Enhancements:
Automate Proxmox cluster scaling.
Implement rolling Proxmox updates with Ansible.
