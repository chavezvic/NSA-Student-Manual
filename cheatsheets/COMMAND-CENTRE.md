# Command Centre

## Windows networking

```powershell
ipconfig /all
Get-NetIPConfiguration
Get-NetAdapter
Get-DnsClientServerAddress
Resolve-DnsName example.com
Test-NetConnection server.example.com -Port 443
Get-NetRoute
arp -a
route print
```

## Windows system

```powershell
Get-ComputerInfo
Get-Service
Get-Process
Get-WinEvent -LogName System -MaxEvents 50
Get-WindowsFeature
Get-Volume
Get-PhysicalDisk
```

## Active Directory

```powershell
Get-ADDomain
Get-ADForest
Get-ADUser -Filter *
Get-ADGroup -Filter *
Get-ADComputer -Filter *
dcdiag
repadmin /replsummary
gpresult /r
```

## Linux

```bash
hostnamectl
ip addr
ip route
ss -tulpn
resolvectl status
dig example.com
systemctl --failed
journalctl -p err -b
df -h
lsblk
free -h
```

## Git

```bash
git status
git add .
git commit -m "Describe the change"
git pull
git push
git log --oneline
git diff
```

## Proxmox

```bash
pveversion -v
qm list
pct list
pvesm status
pvecm status
```

## Cisco IOS basics

```text
show running-config
show startup-config
show ip interface brief
show interfaces status
show vlan brief
show interfaces trunk
show mac address-table
show ip route
show cdp neighbors detail
```
