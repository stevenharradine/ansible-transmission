# ansible-transmission
[Ansible](http://www.ansible.com/) role to set up and configure transmission a web based torrent manager

[![Licence](https://img.shields.io/badge/Licence-ISC-blue.svg)](https://opensource.org/licenses/ISC)
[![Role](https://img.shields.io/ansible/role/6803.svg)](https://galaxy.ansible.com/detail#/role/6803)
[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg)](#)

Tunables
--------
* `transmission_rpc_port` (integer) - the port to listen on
* `transmission_rpc_whitelist` (ip address/cidr): who can access this server

Example Playbook
----------------
    - hosts: servers
      roles:
        - role: stevenharradine.transmission
          transmission_rpc_whitelist: "*"

Contributors
------------
* Steven Harradine
