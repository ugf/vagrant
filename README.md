vagrant
=======

Local development with Vagrant

Setup
-----
* [install virtual box] (https://www.virtualbox.org/wiki/Downloads)
* [install vagrant] (http://downloads.vagrantup.com/)
* setup a base box
    Drop to the command line in the vagrant/package_creation folder and run
`
      vagrant up
      vagrant package
      mkdir ..\boxes
      copy package.box ..\boxes\ubuntu_dev.box
      vagrant destroy -f
`
    This will setup a base box that is similar to our Rightscale ubuntu image.

Examples
--------
To start an operations vm, drop to the command in the vagrant/operations folder and run

`vagrant up`


See also
--------
* http://vagrantup.com
* You can pick from a list of available pre-canned boxes at http://www.vagrantbox.es
