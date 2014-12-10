Ansible Role: mysql
=========

This role installs and configures mysql.

Requirements
------------

This role requires Ansible 1.4 or higher and platform requirements are listed
in the metadata file.

Role Variables
--------------

	- mysql_root_password: password for the mysql root password. default value is root    
	- mysql_dbs: array of databases to be created
	- mysql_users: array of users. Each users must have their name and password. Default value for password is root. `host` and `priv` are optionals

Dependencies
------------

[]

Example Playbook
----------------

	- hosts: all
      roles:
         -  { role: roles/mysql, mysql_root_password: root }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
