# Networking Fundamentals

## Core concepts

- OSI and TCP/IP models
- MAC addresses and Ethernet frames
- IPv4 addressing, CIDR and subnetting
- ARP and neighbor discovery
- Switching and VLANs
- Routing and default gateways
- DNS and DHCP
- NAT and firewall policy
- TCP and UDP
- Common application protocols

## Common ports

| Service | Port | Transport |
|---|---:|---|
| SSH | 22 | TCP |
| DNS | 53 | TCP and UDP |
| DHCP server | 67 | UDP |
| DHCP client | 68 | UDP |
| HTTP | 80 | TCP |
| Kerberos | 88 | TCP and UDP |
| NTP | 123 | UDP |
| HTTPS | 443 | TCP |
| SMB | 445 | TCP |
| RDP | 3389 | TCP and UDP |

Ports are defaults, not guarantees. Confirm the actual configuration.

## Network validation checklist

- Link is up.
- Correct VLAN is assigned.
- Trunk allows required VLANs.
- IP address and mask are correct.
- Default gateway is reachable.
- Required route exists.
- DNS server is reachable.
- Forward and reverse DNS records are correct.
- Firewall policy permits the flow.
- Service listens on the expected port.
