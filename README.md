ansible-role-mongodb
====================

[![Build Status](https://travis-ci.org/kevincoakley/ansible-role-mongodb.svg?branch=master)](https://travis-ci.org/kevincoakley/ansible-role-mongodb)

Install MongoDB (single machine) - https://www.mongodb.com/ . Tested with CentOS 7 and Ubuntu 16.04

Requirements
------------

None

Role Variables
--------------

See defaults/main.yml

Dependencies
------------

None

Example Playbook
----------------

    - name: Test the MongoDB role for stand alone CentOS and Ubuntu systems
      hosts: mongodb
      become: yes
      become_method: sudo
    
      roles:
        - ansible-role-mongodb

License
-------

BSD

Author Information
------------------

Kevin Coakley (https://github.com/kevincoakley)
