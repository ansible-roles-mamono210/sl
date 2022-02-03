[![](https://github.com/ansible-roles-matsumura/sl/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/sl/actions?query=workflow%3Abuild)

Role Description
=========

Installs [sl](https://ja.wikipedia.org/wiki/Sl_(UNIX)) for CentOS7/Stream8.

Requirements
------------

EPEL installed before running this role.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - robertdebock.epel
    - sl
```

License
-------

BSD
