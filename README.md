Role Name
========

Disclaimer: Development in progress, do not use in production, pull requests are welcome!

INCF DataSpace is a datasharing platform aimed at federating NeuroScientific institutions around the world.

Quickstart
----------

    ansible-playbook site.yml -i 192.168.0.1,

Requirements
------------

If you run this on AWS, don't forget to install:

* boto

Role Variables
--------------


Dependencies
------------

  * unattended-upgrades
  * owncloud
  * files_irods
  * postgresql

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

GPLv3
