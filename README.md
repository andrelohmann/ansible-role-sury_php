sury_php
=============

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-sury_php.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-sury_php)

Use this role to install the deb.sury.org php (7.0, 7.1, 7.2, 7.3, 7.4) repository on your debian or ubuntu server.

Requirements
------------

This role requires debian or ubuntu.

Role Variables
--------------

The default set of variables defines an empty array of php packages and needs at best to be overwritten in group_vars/host_vars

    sury_php_packages:
    - php7.4
    - php7.4-mysql

Example Playbook
----------------

    - hosts: php
      roles:
         - andrelohmann.sury_php

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
