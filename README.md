[![](https://github.com/ansible-roles-matsumura/hugo/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/hugo/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/hugo/workflows/molecule/badge.svg)](https://github.com/ansible-roles-matsumura/hugo/actions?query=workflow%3Amolecule)
[![](https://github.com/ansible-roles-matsumura/hugo/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/hugo/actions?query=workflow%3A%22trailing+whitespace%22)
[![](https://github.com/ansible-roles-matsumura/hugo/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/hugo/actions?query=workflow%3Ayamllint)

Role Description
=========

Installs [Hugo](https://gohugo.io) for CentOS7/CentOS8.

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
