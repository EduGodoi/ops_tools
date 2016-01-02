Logging
=========

This is a role to install and configure Sensu and Uchiwa on RHEL 7 to monitor a RHEL OSP Installation.

Requirements
------------

This is a list of requirements for this role: 
- RHEL 7.X
- Valid subscription for the RHEL install. 
- Subscription to  rhel-7-server-openstack-7.0-optools-rpms available. 

Role Variables
--------------



Example Playbook
----------------

In order to facilitate the usage of this role, we are including a file: monitoring.yml.

To run it, point it to your host file and execute ansible playbook: 

ansible-playbook -i path/to/hosts monitoring.yml

Your host file should containt two types of entries: 

monitoring_host -> This point to the IP of your Sensu/Uchiwa server. 
clients -> This points to the IP of the clients where FluentD will gather information.

License
-------

MIT

Author Information
------------------

The author is Julio Villarreal, to contact him you could email julio@linux.com or julio@redhat.com. More info about the author at : http://www.juliovillarreal.com. Thanks!
