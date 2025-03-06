# 🖥️ Proxmox VM Management

## VM Naming Convention:
| Node   | VM ID Range | Purpose |
|--------|------------|---------|
| `proxn1` | 100-199  | Game Servers |
| `proxn2` | 200-299  | AI & Monitoring |

## VM Creation:
To create a new VM:
```bash
qm create 105 --name "new-vm" --memory 4096 --cores 2
```

VM Migration:
To migrate a VM to another node:

```
qm migrate 105 proxn2 --online
```


