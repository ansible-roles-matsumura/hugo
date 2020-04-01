[![](https://github.com/ansible-roles-matsumura/hugo/workflows/Build/badge.svg)](https://github.com/ansible-roles-matsumura/hugo/actions?query=workflow%3ABuild)
[![](https://github.com/ansible-roles-matsumura/hugo/workflows/Lint/badge.svg)](https://github.com/ansible-roles-matsumura/hugo/actions?query=workflow%3ALint)

Role Description
=========

Installs [Hugo](https://gohugo.io) for CentOS7.

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
    - hugo
```

License
-------

BSD
