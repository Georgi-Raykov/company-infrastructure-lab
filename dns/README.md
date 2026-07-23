# DNS Server Documentation

## Server

Hostname:
dns01.company.local

IP Address:
192.168.60.30


## Role

DNS server provides:

- Forward DNS resolution
- Reverse DNS resolution
- Internal hostname resolution


## Software

Service:
BIND9 (named)

Configuration:

/etc/named.conf

Zone configuration:

/etc/named.rfc1912.zones


## DNS Zones

Forward zone:

company.local


Reverse zones:

192.168.60.0/24
192.168.50.0/24


## Testing

Forward lookup:

dig dhcp01.company.local @192.168.60.30


Reverse lookup:

dig -x 192.168.60.30 @192.168.60.30
