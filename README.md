[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/sl/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/sl/tree/main)

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
