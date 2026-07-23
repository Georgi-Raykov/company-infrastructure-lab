# Firewall Tests


## Active Zones

Command:

firewall-cmd --get-active-zones



## Zone Configuration

Command:

firewall-cmd --list-all



## Policy Verification

Commands:

firewall-cmd --info-policy internal-to-wan

firewall-cmd --info-policy internal-to-dmz



## Connectivity Tests

From admin01:

Ping gateway:

ping 192.168.50.1


Internet test:

ping 8.8.8.8


DNS test:

getent hosts google.com


SSH test:

ssh linuxlabs@dns01.company.local
