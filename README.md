DataSpace
=========

Disclaimer: Development in progress, do not use in production, pull requests are welcome!

INCF DataSpace is a datasharing platform aimed at federating NeuroScientific institutions around the world.

This playbook deploys:

	* OwnCloud 7 + files_irods app
	* OpenStack Swift
	* iRODS backend for backwards compatibility with older stores
	* INCF-specific configurations

Quickstart
----------

    ansible-playbook site.yml -i 192.168.0.1,

License
-------

GPLv3
