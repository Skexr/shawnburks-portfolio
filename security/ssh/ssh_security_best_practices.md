# 🔑 SSH Security Best Practices

## Overview
SSH security is enforced through **strict access policies** to prevent unauthorized access.

## Configured Security Measures:
- **Disable Root Login:** Only `skex` user is allowed
- **Key-Based Authentication:** Password logins disabled
- **Custom SSH Port:** Non-default SSH port used
- **Fail2Ban Protection:** Auto-ban on failed login attempts

## Configuration File:
Located at:  /etc/ssh/sshd_config

Example Configuration:
```ini
PermitRootLogin no
PasswordAuthentication no
Port 2202
AllowUsers skex
```
Future Enhancements:
Automate SSH key distribution using Ansible.
Implement multi-factor authentication (MFA) for SSH logins.
