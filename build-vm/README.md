###Please follow these steps to spin up a virtual machine for aPET using vagrant script:
1. Download and Install [Vagrant](https://www.vagrantup.com/downloads.html) on the host machine.
2. Download and Install [Virtual Box](https://www.virtualbox.org/wiki/Downloads) on the host machine.
2. Download the [Vagrantfile](https://github.com/SoftwareEngineeringToolDemos/FSE-2013-aPET/blob/master/build-vm/Vagrantfile) from [build-vm](https://github.com/SoftwareEngineeringToolDemos/FSE-2013-aPET/tree/master/build-vm) directory to your machine.
3. In the host machine, cd into the directory that contains the Vagrantfile and run the command `"vagrant up"`.
4. The command `"vagrant up"` will create a Ubuntu VM with Java and Eclipse installed in it.

###Note:
* The VM boots up quickly and can be viewed from VirtualBox. But the "vagrant up" command runs up approximately for 15-20 minutes.
* VM Login Details:

 ` Username: vagrant`
  
  `Password: vagrant`

###Acknowledgements:
Used vagrant virtual box image of [64 bit ubuntu](https://vagrantcloud.com/box-cutter/boxes/ubuntu1404-desktop).

###References:
[Vagrant Documentation](https://docs.vagrantup.com/v2/getting-started/)

[Vagrant Blog](https://www.vagrantup.com/blog.html)

[Tutorial to install java](https://www.digitalocean.com/community/tutorials/how-to-install-java-on-ubuntu-with-apt-get)

[Ubuntu1404-desktop Virtual Box](https://vagrantcloud.com/box-cutter/boxes/ubuntu1404-desktop)
