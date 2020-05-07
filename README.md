[![](https://github.com/ansible-roles-matsumura/hugo/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/hugo/actions?query=workflow%3Ayamllint)
[![](https://github.com/ansible-roles-matsumura/hugo/workflows/ansible-playbook/badge.svg)](https://github.com/ansible-roles-matsumura/hugo/actions?query=workflow%3Aansible-playbook)
[![](https://github.com/ansible-roles-matsumura/hugo/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/hugo/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/hugo/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/hugo/actions?query=workflow%3A%22trailing+whitespace%22)

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
