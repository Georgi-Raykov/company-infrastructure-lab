# SSH Hardening


## Recommended Configuration


Disable root login:

PermitRootLogin no


Disable password authentication:

PasswordAuthentication no


Allow administrative user:

AllowUsers linuxlabs


## Apply changes

Restart or reload SSH service:

systemctl reload sshd


## Verification

Test connection from admin01 before closing old session.
