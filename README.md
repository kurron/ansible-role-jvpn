Role Name
=========

Installation of tools than any self-respecting SQL developer loves and needs.

Requirements
------------

TODO

Role Variables
--------------

* sql_datagrip_install: true
* sql_datagrip_version: 2016.2.6
* sql_mysql_tools_install: true
* sql_postgresql_tools_install: true

Dependencies
------------

* kurron.jdk

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.sql-developer, sql_postgresql_tools_install: true }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
