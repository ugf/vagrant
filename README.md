vagrant
=======

Local development with Vagrant

Setup
-----
* [install virtual box] (https://www.virtualbox.org/wiki/Downloads)
* [install vagrant] (http://downloads.vagrantup.com/)
* setup a base box

Drop to the command line in the vagrant/package_creation folder and run

`vagrant up`

`del package.box` If package.box exists

`vagrant package`

`copy package.box ..\boxes\ubuntu_dev.box`

`vagrant destroy -f`

This will setup a base box that is similar to our Rightscale ubuntu image named ubuntu_dev.

Examples
--------
To start an operations vm, drop to the command in the vagrant/operations folder and run

`vagrant box remove ubuntu_dev` If an ubuntu_dev box already exists from a previous package

`vagrant up`

To ssh in (from windows) use putty and connect to port 2222 against ip 127.0.0.1.  Use the ppk file that is in the boxes
folder.

See also
--------
* http://vagrantup.com
* You can pick from a list of available pre-canned boxes at http://www.vagrantbox.es
