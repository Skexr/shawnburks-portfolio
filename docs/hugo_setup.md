# 📄 Deploying a Hugo Website on a Self-Hosted VM

## **Overview**
This guide documents the process of deploying a **Hugo-based static website** for `burksfamily.com` on a self-hosted Proxmox VM using **Nginx**.

---

## **1️⃣ VM Setup**
**Recommended Specs:**
| Component  | Recommended |
|------------|------------|
| OS        | Ubuntu 24.04 LTS |
| CPU       | 2 vCPUs |
| RAM       | 4GB+ |
| Storage   | 20GB SSD |
| IP Address | `192.168.50.X` |

---

## **2️⃣ Install Hugo & Clone the Repo**
```bash
sudo apt update && sudo apt install -y hugo git
cd /var/www/
git clone https://github.com/Skexr/shawnburks-portfolio.git hugo-site
cd hugo-site
hugo
