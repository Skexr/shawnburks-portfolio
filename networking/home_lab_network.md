# 🏠 Home Lab Network Overview

## **Network Topology**
- **Router**: Asus RT-AXE7800 (Main Internet Gateway)
- **Proxmox Hosts**:
  - `proxn1`: Game servers, monitoring, automation
  - `proxn2`: AI server, backup system
- **Storage Networks**: 
  - NFS for backups
  - iSCSI (Planned for expansion)

## **Current Network Configuration**
# 🏠 Home Lab Network Overview

## **Network Topology**
- **Router**: Asus RT-AXE7800 (Main Internet Gateway)
- **Proxmox Hosts**:
  - `proxn1`: Game servers, monitoring, automation
  - `proxn2`: AI server, backup system
- **Storage Networks**: 
  - NFS for backups
  - iSCSI (Planned for expansion)

## **Current Network Configuration**
reverse DNS list	dystopia.games	IP Address	MAC Address	ports		ssh port	additional ports
npm	npm.dystopia.games	192.168.50.10	BC:24:11:8C:B4:97	80:81:443		210	8080
proxn1	proxn1.dystopia.games	192.168.50.12	2A:BE:92:DC:CF:DE	8006	78:2b:cb:3b:07:1a	222	
proxn2	proxn2.dystopia.games	192.168.50.13	9C:7B:EF:27:F1:F8	7006		223	
pbs	pbs.dystopia.games	192.168.50.13	9C:7B:EF:27:F1:F8	8007			
graf	graf.dystopia.games	192.168.50.14	BC:24:11:DE:D7:70	3000		224	
wings1	wings1.dystopia.games	192.168.50.15	BC:24:11:83:B2:0F	2021: 8444: 25700-26000		225	25700-26000
wings2	wings2.dystopia.games	192.168.50.16	BC:24:11:76:32:8F	2020:8446:27000-27100		226	27000-27100
nfs	nfs.dystopia.games	192.168.50.17	BC:24:11:9D:F8:75	111:2049		227	
jarvis	jarvis.dystopia.games	192.168.50.18	BC:24:11:7D:60:44	4000		228	
idrac1	idrac1.dystopia.games	192.168.50.19	78:2B:CB:38:07:22			229	
games	games.dystopia.games	192.168.50.20	BC:24:11:3A:0D:AF	8447		230	
ptero	ptero.dystopia.games	192.168.50.21	BC:24:11:88:3D:E7	8445		231	
ansible	ansible.dystopia.games	192.168.50.22	BC:24:11:EA:EA:EE			232	
Kali	Kali.dystopia.games	192.168.50.23	BC:24:11:44:F7:95				
HoneyPot	HoneyPot.dystopia.games	192.168.50.64	40:B0:76:4D:CB:4C				


## **Planned Upgrades**
- Implement VLAN segmentation for **better isolation**.
- Deploy a dedicated **management VLAN** for Proxmox.

## **Planned Upgrades**
- Implement VLAN segmentation for **better isolation**.
- Deploy a dedicated **management VLAN** for Proxmox.
