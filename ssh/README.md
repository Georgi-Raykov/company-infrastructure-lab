# SSH Administration Documentation


## Management Model

The infrastructure is managed from:

admin01.company.local


SSH access is configured to:

- gateway.company.local
- dns01.company.local
- dhcp01.company.local


## Authentication

Authentication method:

SSH public key authentication


Password authentication is planned to be disabled after validation.


## Security Goals

- No direct root login
- Key-based authentication
- Restricted administrative access
- Firewall controlled SSH access
