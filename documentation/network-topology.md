# Network Topology

## Overview

This project represents a small enterprise infrastructure lab.

Main components:

- Gateway firewall/router
- Internal LAN network
- DMZ network
- DNS server
- DHCP server
- Administrative workstation


## Network Segmentation

### Internal LAN

Network:
192.168.50.0/24

Purpose:
- Administration
- User clients
- DHCP clients


### DMZ

Network:
192.168.60.0/24

Purpose:
- Infrastructure servers
- Internal services


## Hosts

| Hostname | IP Address | Role |
|----------|------------|------|
| gateway | 192.168.50.1 | Firewall / Router |
| admin01 | 192.168.50.100 | Management workstation |
| dhcp01 | 192.168.50.5 | DHCP server |
| dns01 | 192.168.60.30 | DNS server |


## Management Flow

Administrator connects to admin01 and manages:

- gateway
- dns01
- dhcp01

using SSH key authentication.
