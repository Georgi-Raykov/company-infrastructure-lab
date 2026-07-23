# Firewall Documentation

## Device

Hostname:

gateway.company.local


## Role

Gateway provides:

- Network routing
- Firewall protection
- Network segmentation
- Internet access control


## Firewall Software

firewalld

Backend:

nftables


## Interfaces

Internal LAN:

192.168.50.0/24


DMZ:

192.168.60.0/24


External:

Internet/WAN connection


## Management

Firewall is administered through SSH from admin01.
