# Ansible Projects
# ⚙️ Ansible Automation in My Home Lab

## Overview
Ansible is used in my home lab for **automating server provisioning, configuration management, and network security**.

## 🔹 Use Cases
- **Proxmox VM Automation** – Deploy and manage virtual machines with Ansible playbooks.
- **Network Configuration** – Automate firewall rules, VPN configurations, and Cloudflare DDNS updates.
- **Security Hardening** – Set up Fail2Ban, SSH hardening, and firewall automation.
- **Backup Automation** – Automate backups for Proxmox configurations and game servers.

## 🔹 Ansible Playbooks
| Playbook Name       | Purpose |
|---------------------|---------|
| `proxmox-vm.yml`   | Deploys new VMs in Proxmox |
| `firewall-setup.yml` | Automates firewall rules |
| `fail2ban-setup.yml` | Sets up Fail2Ban on all servers |
| `game-server-deploy.yml` | Automates Pterodactyl game server provisioning |

## 🔹 Sample Proxmox VM Deployment Playbook
```yaml
- name: Create VM in Proxmox
  hosts: proxmox
  tasks:
    - name: Clone template
      community.general.proxmox_kvm:
        api_user: "{{ proxmox_user }}"
        api_password: "{{ proxmox_password }}"
        api_host: "{{ proxmox_host }}"
        node: proxmox1
        vmid: 100
        name: ansible-deployed-vm
        clone: ubuntu-template
        cores: 2
        memory: 4096
