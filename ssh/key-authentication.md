# SSH Key Authentication


## Key Generation

Generated on admin01:

ssh-keygen


## Public Key Deployment

Public key copied to servers:

ssh-copy-id linuxlabs@server


## Authorized Keys

Location:

~/.ssh/authorized_keys


## Permissions

SSH directory:

chmod 700 ~/.ssh


Authorized keys:

chmod 600 ~/.ssh/authorized_keys


## SELinux

Verify context:

ls -Z ~/.ssh/authorized_keys


Expected context:

ssh_home_t
