[![Build Status](https://travis-ci.org/danie1cohen/ansible-virtualenv3.svg?branch=master)](https://travis-ci.org/danie1cohen/ansible-virtualenv3)

Virtualenv3
=========

This role sets up a virtualenv running a python3 executable.

Requirements
------------

None

Role Variables
--------------

project
workon_home


Dependencies
------------

None

Example Playbook
----------------


    - hosts: webservers
      roles:
         - virtualenv3

License
-------

BSD

Author Information
------------------

[Dan Cohen](https://www.dancohen.io)
