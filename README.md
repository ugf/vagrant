vagrant
=======

Local development with Vagrant

Setup
-----
* [install virtual box] (https://www.virtualbox.org/wiki/Downloads)
* [install vagrant] (http://downloads.vagrantup.com/)

Examples
--------
From the command line run:

    vagrant box add ubuntu http://dl.dropbox.com/u/4031118/Vagrant/ubuntu-12.04.1-server-i686-virtual.box

This command will download a ubuntu box to your local machine and associate it with the alias *ubuntu*.

To start an operations vm, drop to the command in the vagrant/operations folder and run

`vagrant up`


See also
--------
* http://vagrantup.com
* You can pick from a list of available pre-canned boxes at http://www.vagrantbox.es
