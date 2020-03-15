[![](https://github.com/ansible-roles-matsumura/sl/workflows/Ansible%20Playbook/badge.svg)](https://github.com/ansible-roles-matsumura/sl/actions)

Role Name
=========

Installs sl for CentOS7.

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
