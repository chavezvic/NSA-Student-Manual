# Playbook: Linux Service Down

```bash
systemctl status <SERVICE>
journalctl -u <SERVICE>
ss -tulpn
```

Check configuration, permissions, dependencies, firewall, storage and recent changes.
