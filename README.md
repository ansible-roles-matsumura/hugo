[![](https://github.com/ansible-roles-matsumura/hugo/workflows/Build/badge.svg)](https://github.com/ansible-roles-matsumura/hugo/actions?query=workflow%3ABuild)
[![](https://github.com/ansible-roles-matsumura/hugo/workflows/Lint/badge.svg)](https://github.com/ansible-roles-matsumura/hugo/actions?query=workflow%3ALint)
[![](https://github.com/ansible-roles-matsumura/hugo/workflows/Trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/hugo/actions?query=workflow%3A%22Trailing+whitespace%22)

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
