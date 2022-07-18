# Pritnul VPN server

This roles helps to install Pritunl VPN Server across Ubuntu variants.

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Role Variables

The variables that can be passed to this role and a brief description about them are as follows:
```
  mongodb_versions: 5.0              # The version of mongodb to install

```
## Examples

Install VPN Server
```
- hosts: all
  roles:
    - { role: pritunl, mongodb_versions: 5.0 }
```
