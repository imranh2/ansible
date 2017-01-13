# Imran's Ansible Stuff

A place for me to keep ansible I've written that others might find useful.

For examples on how to use each role look at $rolename-example.yml

## Current Roles

* common - random prep
* letsencrypt - Get letsencrypt ssl certs using the webroot directive
* network - Deploy network configs for Debian and RedHat based systems: normal interfaces (static, dhcp), bridges, bonds, vlans (via the interface.vlanid syntax)
* dns-server - Setup a master or slave DNS server for a zone
