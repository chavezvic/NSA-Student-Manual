# Proxmox VE Operations

## Key concepts

- Nodes and clusters
- KVM virtual machines
- LXC containers
- Linux bridges
- VLAN-aware networking
- Storage pools
- Templates and clones
- Snapshots
- Backups
- High availability
- Role-based access control

## Before creating a VM

Record:

- VM ID
- Hostname
- Purpose
- vCPU
- Memory
- Disk
- Network bridge
- VLAN tag
- IP address
- Operating system
- Owner
- Backup policy

## Useful commands

```bash
pveversion -v
pvesh get /nodes
qm list
qm config <VMID>
qm status <VMID>
pct list
pvesm status
pvecm status
ip link
bridge vlan show
```

## Important distinction

A snapshot is not a complete backup. Snapshots are useful for short-term rollback, while backups support recovery from storage loss, corruption or accidental deletion.
