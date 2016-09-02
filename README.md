Ansible Role - Dotdeb
=====================

[![Build Status](https://travis-ci.org/Irvyne/ansible-role-dotdeb.svg?branch=master)](https://travis-ci.org/Irvyne/ansible-role-dotdeb)

Install Dotdeb repositories for Debian 6 to 8.

Requirements
------------

Ansible >= 2.1

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Install Dotdeb repositories on supported Debian hosts.

```yaml
- hosts: all
  roles:
    - { role: dotdeb }
```

License
-------

MIT

Author Information
------------------

Thibaud BARDIN - https://github.com/Irvyne
