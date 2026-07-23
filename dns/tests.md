# DNS Tests

## Forward lookup

dig dhcp01.company.local @192.168.60.30


## Reverse lookup

dig -x 192.168.60.30 @192.168.60.30

dig -x 192.168.50.5 @192.168.60.30
