# Linux Server Operations

## Core administration areas

- Package management
- Users and groups
- sudo
- Files and permissions
- Services
- Networking
- Storage
- Logs
- SSH
- Scheduled tasks
- Backup
- Security updates

## Essential commands

```bash
hostnamectl
ip addr
ip route
resolvectl status
ss -tulpn
systemctl --failed
systemctl status <service>
journalctl -u <service>
df -h
lsblk
free -h
top
ps aux
sudo apt update
sudo apt upgrade
```

## Basic hardening

- Patch regularly.
- Use SSH keys where possible.
- Disable unused services.
- Restrict sudo.
- Configure a host firewall.
- Review listening ports.
- Protect private keys.
- Monitor authentication logs.
- Back up configuration and data.
- Test restoration.
