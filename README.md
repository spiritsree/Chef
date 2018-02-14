# Chef

## Table of Contents

* [Setting Up Workstation Environment](#setting-up-workstation-environment)


## Setting Up Workstation Environment

* Install VirtualBox from https://www.virtualbox.org
* Verify install `$ VBoxManage --version`
* Download and install vagrant from https://www.vagrantup.com/downloads.html
* Verify install `$ vagrant --version`
* Add ubuntu to vagrant box list `$ vagrant box add bento/ubuntu-14.04 --provider=virtualbox`
* Initialize vagrant `$ vagrant init bento/ubuntu-14.04`
* `$ vagrant init`              # Creates a Vagrant file, used to specify virtual machine settings
* `$ vagrant up`	              # Spins up the virtual machine using the Vagrant  le
* `$ vagrant status`            # Lists virtual machines and current status—’running’ means machine is available for SSH
* `$ vagrant ssh-config`        # Lists connection details for running instances
* `$ vagrant suspend`           # Save machine state and shut down
* `$ vagrant destroy --force`   # Destroy all running virtual machines
* `$ vagrant ssh`               # Login to the box
* Install ChefDK  `curl https://omnitruck.chef.io/install.sh | sudo bash -s -- -P chefdk -c stable -v 1.3.43`
* Verify install `$ chef --version `

