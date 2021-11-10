# Terraform-cli

This Vagrant file specifies a script execution to a shell script in a different Github repository to install the latest version of terraform on the virtual machine. 

# Prerequisites

Vagrant [See documentation](https://www.vagrantup.com/docs/installation)  
Virtualbox [See documentation](https://www.virtualbox.org/wiki/Downloads)

# How to

1. Clone the repository to your local machine
```
git clone https://github.com/automodule/vagrant.git
```
2. Change your directory
```
cd vagrant/terraform-cli
```
3. Start a virtual machine with Vagrant
```
vagrant up
```
4. ssh into the virtual machine with Vagrant.
```
vagrant ssh
```
5. Latest terraform should now be available to you
```
terraform -version
```
6. exit out of the vagrant machine
```
exit
```
7. Stop the vagrant machine
```
vagrant halt
```
8. When you are completely done you can remove it
```
vagrant destroy
```