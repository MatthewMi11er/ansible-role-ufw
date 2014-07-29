Ansible Role: UFW
========

Install and do a base configuration of a firewall using ___UFW___

Specific ports should be opened by the roles that need them.

Requirements
------------

None.

_Note_: This role has only be tested on Ubuntu. If you want to extend it feel free to contribute.

Role Variables
--------------

- ansible\_ssh\_port (___22___)
- ufw\_logging (___on___|off)

Dependencies
------------

None.

Example Playbook
-------------------------
```YML
- hosts: servers
  roles:
    - { role: matthewmi11er.ufw }
```
or 
```YML
#meta
dependencies
  - { role: matthewmi11er.ufw }
```
License
-------

MIT

Author Information
------------------
