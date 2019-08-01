DB
=========

[![Build Status](https://travis-ci.com/SJay3/ansible-otus-db.svg?branch=master)](https://travis-ci.com/SJay3/ansible-otus-db)

Role for install mongodb. Simple role used by otus.

Requirements
------------

For test with molecul you need molecule and testinfra

Role Variables
--------------

mongo_port: 27017
mongo_bind_ip: 127.0.0.1
env: local used for organized by environments

Dependencies
------------
none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: db-servers
      roles:
         - db

License
-------

BSD

Author Information
------------------

SJ
