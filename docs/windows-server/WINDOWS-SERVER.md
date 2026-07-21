# Windows Server Operations

## Build order

1. Install Windows Server.
2. Patch the system.
3. Configure hostname.
4. Configure static IP, gateway and DNS.
5. Set time zone and confirm time synchronization.
6. Install required roles.
7. Configure security and remote management.
8. Validate services.
9. Back up the configuration.
10. Document the final state.

## Active Directory design reminders

- Use a registered domain or delegated subdomain for production.
- Separate administrative and standard user accounts.
- Organize OUs for management and policy application.
- Use security groups for permissions.
- Avoid assigning permissions directly to individual users.
- Protect privileged groups.
- Monitor replication and DNS health.

## Health commands

```powershell
Get-ComputerInfo
Get-NetIPConfiguration
Get-WindowsFeature
Get-Service
Get-WinEvent -LogName System -MaxEvents 20
dcdiag
repadmin /replsummary
Get-ADDomain
Get-ADForest
Get-DnsServerZone
Get-DhcpServerv4Scope
```

## Permission model

A common model is:

```text
Accounts → Global groups → Domain local groups → Permissions
```
