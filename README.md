ansible-role-php
=========

PHP configuration

Requirements
------------

This role has only been tested on EL 6 systems using Ansible 1.9.

Role Variables
--------------

__php_modules__: An array of php extension names to optionally install with php.


Example Playbook
----------------

```
- hosts: webservers
  roles:
    - { role: bitmotive.ansible-role-php, tags: "php" }
```

License
-------

MIT
