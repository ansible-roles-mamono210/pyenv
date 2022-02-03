[![](https://github.com/ansible-roles-matsumura/pyenv/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/pyenv/actions?query=workflow%3Abuild)

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
