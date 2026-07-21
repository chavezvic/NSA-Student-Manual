# Troubleshooting Method

## The seven-stage method

1. Identify the problem.
2. Establish a theory.
3. Test the theory.
4. Plan the fix and assess impact.
5. Implement the fix.
6. Verify full functionality.
7. Document findings and prevention.

## Ask these questions first

- What changed?
- When did it last work?
- Who or what is affected?
- Is the problem constant or intermittent?
- Can it be reproduced?
- What is the exact error?
- What do the logs show at that time?
- Is the problem local, network-wide or service-wide?

## Layered diagnostic sequence

```text
Power and hardware
Physical link
Interface configuration
IP address and subnet
Default gateway
Routing
DNS
Transport port
Service
Authentication and authorization
Application
```

## Fast network workflow

```powershell
ipconfig /all
Get-NetIPConfiguration
ping <gateway>
tracert <destination>
Resolve-DnsName <hostname>
Test-NetConnection <host> -Port <port>
route print
arp -a
```

```bash
ip addr
ip route
ping -c 4 <gateway>
tracepath <destination>
resolvectl status
dig <hostname>
nc -vz <host> <port>
ss -tulpn
```

## Root cause record

Document:

- Symptom
- Scope
- Timeline
- Evidence
- Root cause
- Resolution
- Validation
- Prevention
- Remaining risk
