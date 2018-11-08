# Vagrant
Vagrant file to download 3 Junos images


Vagrant: Virtual Machine manager, Spins up virtual machines
1) Download Vagrant from internet 'https://www.vagrantup.com/downloads.html'
2) Go to the location where you have copied the above file and saved through cmd. Note: the file should be saved as 'Vagrantfile'
command: 'vagrant plugin install vagrant-junos'
command: 'vagrant plugin install vagrant-host-shell'  (Plugin, Vagrant knows this is not windows, this is junos)
3) vagrant up
4) Vagrant ssh jumphost
5) Download: epel-release, git ansible, python-pip, net-tools, , vim
6) pip install junos-eznc jxmlease
