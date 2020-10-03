DEPRECATED. Please check the new nextcloud role https://github.com/swcc/ansible-nextcloud
=========

[![Build Status](https://travis-ci.org/swcc/ansible-owncloud-role.svg?branch=master)](https://travis-ci.org/swcc/ansible-owncloud-role)

Install owncloud packages for Debian.

This playbook simply installs owncloud files on your server.

Example Playbook Usage
----------------

    - hosts: servers
      roles:
        - role: swcc.owncloud

Role Dependencies
----------------

- `paulRbr.php-fpm`

License
-------

GPLv3
