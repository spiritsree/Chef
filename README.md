# Chef

## Table of Contents

* [Setting Up Workstation Environment](#setting-up-workstation-environment)


## Setting Up Workstation Environment

* Install VirtualBox from https://www.virtualbox.org
* `$ VBoxManage --version`                    # Verify install
* Download and install vagrant from https://www.vagrantup.com/downloads.html
* `$ vagrant --version`                       # Verify install
* `$ vagrant box add bento/ubuntu-16.04 --provider=virtualbox`                                # Add a box to vagrant box list.
* `$ vagrant box remove bento/ubuntu-16.04 --box-version 201708.22.0 --provider virtualbox`   # Remove a box from local list.
* `$ vagrant init bento/ubuntu-16.04`         # Initialize vagrant with the added box.
* `$ vagrant init`                            # Creates a Vagrant file, used to specify virtual machine settings.
* `$ vagrant up`	                            # Spins up the virtual machine using the Vagrant file.
* `$ vagrant status`                          # Lists virtual machines and current status—’running’ means machine is available for SSH.
* `$ vagrant ssh-config`                      # Lists connection details for running instances.
* `$ vagrant suspend`                         # Save machine state and shutdown.
* `$ vagrant destroy --force`                 # Destroy all running virtual machines.
* `$ vagrant ssh`                             # Login to the box.
* Install ChefDK  `curl https://omnitruck.chef.io/install.sh | sudo bash -s -- -P chefdk -c stable -v 2.1.11`
* `$ chef --version `                         # Verify install.

