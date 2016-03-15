Die, Die, My Vagrant
=========================

A highly re-usable simple web development vagrant box:
  * Based on CentOS7 because fuck ubuntu
  * Provides Ansible (Local) as a provisioner.
  * Leans on the provisioner and plugins to do all the work at runtime, not a custom managed vagrant box that will get out of date quickly.

Requirements
--------------
  * VirtualBox 5+
  * Vagrant 1.8+
  * Vagrant Plugins:
    * vagrant-vbguest (`vagrant plugin install vagrant-vbguest`)

Usage
------
1. clone
2. vagrant plugin install vagrant-vbguest
3. vagrant up
4. stick your files in ./docroot
5. point your browser http://die.lvh.me


Credits
-------
  1. Much of the ansible playbook was lifted from https://github.com/ansible/ansible-examples, particularly 
     https://github.com/ansible/ansible-examples/tree/master/wordpress-nginx_rhel7

