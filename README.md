# Company Infrastructure Lab


## Overview

This project represents a small enterprise Linux infrastructure environment built for learning and practical system administration.

The goal of this lab is to simulate a real company infrastructure with network segmentation, core services, security controls and administration practices.


## Architecture

The infrastructure consists of:

- Gateway firewall/router
- Internal LAN network
- DMZ network
- DNS server
- DHCP server
- Administrative workstation


## Network Design


### Internal LAN

Network:

192.168.50.0/24


Purpose:

- Administration
- Client systems
- DHCP clients



### DMZ

Network:

192.168.60.0/24


Purpose:

- Infrastructure servers
- Controlled services



## Systems


| Hostname | IP Address | Role |
|----------|------------|------|
| gateway | 192.168.50.1 | Firewall / Router |
| admin01 | 192.168.50.100 | Administration workstation |
| dhcp01 | 192.168.50.5 | DHCP Server |
| dns01 | 192.168.60.30 | DNS Server |



## Technologies Used

- AlmaLinux
- firewalld
- BIND DNS
- ISC DHCP
- OpenSSH
- Git
- GitHub



## Implemented Features

✅ Network segmentation  
✅ Firewall zones and policies  
✅ Internal DNS resolution  
✅ Reverse DNS resolution  
✅ DHCP service  
✅ SSH key authentication  
✅ Infrastructure documentation  


## Management Model

Administration is performed from:

admin01


SSH key authentication is used to manage:

- gateway
- dns01
- dhcp01



## Future Improvements

Planned additions:

- Monitoring
- Backup solution
- LVM scenarios
- Incident response simulations
- Security hardening
- Ansible automation
