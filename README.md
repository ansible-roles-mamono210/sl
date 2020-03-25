[![](https://github.com/ansible-roles-matsumura/sl/workflows/Build/badge.svg)](https://github.com/ansible-roles-matsumura/sl/actions?query=workflow%3ABuild)
[![](https://github.com/ansible-roles-matsumura/sl/workflows/Lint/badge.svg)](https://github.com/ansible-roles-matsumura/sl/actions?query=workflow%3ALint)

Role Description
=========

Installs [sl](https://ja.wikipedia.org/wiki/Sl_(UNIX)) for CentOS7.

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
    - geerlingguy.repo-epel
    - sl
```

License
-------

BSD
