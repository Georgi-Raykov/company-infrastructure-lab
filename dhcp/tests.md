# DHCP Tests

## Client verification

Check IP address:

ip a


## Routing

Check default gateway:

ip route


## DNS configuration

Check resolver:

cat /etc/resolv.conf


## Expected result

Client should receive:

- IP address from DHCP pool
- Default gateway 192.168.50.1
- DNS server 192.168.60.30
- Domain company.local
