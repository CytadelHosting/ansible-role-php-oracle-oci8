Role Name
=========

Ansible role to install PHP OCI8 Oracle driver + dependancies (Oracle Instant Client).

Tested on Debian only, but should work on other Linux flavours

Requirements
------------

PHP and PECL installed
For example
* geerlingguy.php
* geerlingguy.php-pecl

Role Variables
--------------

TODO

Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: CytadelHosting.php-oracle-oci8, x: 42 }

License
-------

MIT

Author Information
------------------

This role was first created in 2021 by [Sylvain Roche](https://github.com/niavlysAO).

[Cytadel](https://www.cytadel.fr/) is a Hosting Company based in Lyon, France.

Cytadel is a business unit of [JETPULP](https://www.jetpulp.fr/), and is a member of [Altavia Group](https://www.altavia.com/).
