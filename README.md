[![](https://github.com/ansible-roles-matsumura/sl/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/sl/actions?query=workflow%3Ayamllint)
[![](https://github.com/ansible-roles-matsumura/sl/workflows/ansible-playbook/badge.svg)](https://github.com/ansible-roles-matsumura/sl/actions?query=workflow%3Aansible-playbook)
[![](https://github.com/ansible-roles-matsumura/sl/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/sl/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/sl/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/sl/actions?query=workflow%3A%22trailing+whitespace%22)

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
