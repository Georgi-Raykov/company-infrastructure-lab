# Company Infrastructure Lab

## Architecture

The environment consists of:

- gateway firewall/router
- DNS server
- DHCP server
- Administrative workstation

## Components

### gateway
Role:
- Firewall
- Router
- Network segmentation
- Internet access control

### dns01
IP:
192.168.60.30

Role:
- Internal DNS server
- Forward and reverse DNS zones

### dhcp01
IP:
192.168.50.5

Role:
- DHCP service
- Client IP assignment

### admin01
Role:
- Administrative workstation
- SSH management point
- Future Ansible control node
