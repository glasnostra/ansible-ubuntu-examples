# Ubuntu-Ansible-Examples

This example will install nginx, php5-fpm and mysql using ansible to Ubuntu-based Vagrant.

### Version
0.0.1

### Required

This example uses a number of software to work properly:

* [Vagrant] - Headless VM
* [Ansible] - Simple Configuration Manager

### Howto

Open your favorite Terminal and run these commands.

First: Install roles
```sh
$ ansible-galaxy install lagilaper.nginx 
$ ansible-galaxy install lagilaper.php5-fpm
```

Second:
```sh
$ vagrant up
```

(Optional) Third: If the VM is already provisioned
```sh
$ vagrant provision
```

### Todo's

 - Test in different boxes and scenarios
 - Add more samples
 - Add centOS / RHEL based for php5-fpm and mysql roles
 - Fix some bugs :)

License
----

MIT

[vagrant]:http://vagrantup.com/
[ansible]:http://docs.ansible.com/intro_installation.html
