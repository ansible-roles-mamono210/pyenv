[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/pyenv/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/pyenv/tree/main)

Role Description
=========

Installs [pyenv](https://github.com/pyenv/pyenv) for CentOS7/Stream8.

Requirements
------------

None

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
    - pyenv
```

License
-------

BSD
