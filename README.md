sury_php
=============

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-sury_php.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-sury_php)

Use this role to install the deb.sury.org php (7.0, 7.1, 7.2) repository on your debian or ubuntu server.

Requirements
------------

This role requires debian or ubuntu.

Example Playbook
----------------

    - hosts: php
      roles:
         - { role: andrelohmann.ansible-role-sury_php }

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
