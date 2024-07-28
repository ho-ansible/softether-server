# Ansible role: softether-server
SoftEther VPN server (SSTP)

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `softether_port` (default: 443): TCP port to listen on

## Playbooks
+ `main.yml`: apply role
+ `uninstall.yml`: remove. Run prior to removing host from inventory group.

## Dependencies
+ [ho-ansible.systemd](https://github.com/ho-ansible/systemd)

## License
+ Ansible role licensed [MIT](LICENSE)

## Author Information
+ Ansible role by [Sean Ho](https://github.com/ho-ansible/)
