Role Name
=========

Connect to a Juniper VPN under Ubuntu.

Requirements
------------

`kurron.base`

Role Variables
--------------

* jvpn_install: true
* jvpn_vpn_host: portal.transparent.com
* jvpn_vpn_port: 443
* jvpn_vpn_url: url_1
* jvpn_vpn_realm: Macintosh_Users
* jvpn_vpn_username: CHANGEME
* jvpn_vpn_password: CHANGEME

Dependencies
------------
TODO

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.jvpn }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
