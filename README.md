[![](https://github.com/ansible-roles-matsumura/sl/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/sl/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/sl/workflows/molecule/badge.svg)](https://github.com/ansible-roles-matsumura/sl/actions?query=workflow%3Amolecule)
[![](https://github.com/ansible-roles-matsumura/sl/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/sl/actions?query=workflow%3A%22trailing+whitespace%22)
[![](https://github.com/ansible-roles-matsumura/sl/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/sl/actions?query=workflow%3Ayamllint)

Role Description
=========

Installs [sl](https://ja.wikipedia.org/wiki/Sl_(UNIX)) for CentOS7/CentOS8.

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
