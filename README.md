# ansible-role-sysdig

Ansible role for installing sysdig, following the instructions on [the sysdig website](http://www.sysdig.org/install/).

## Requirements
Designed for Ubuntu 16.04 and CentOS 7.

## Example Playbook

```yml
- hosts: all
  roles: 
    - { role: sysdig }
```
