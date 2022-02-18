1. Name the providers supported by Vagrant out-of-the-box.
    - Microsoft Hyper-V
    - Docker
    - VirtualBox


2. Name a plug-in provider for vagrant.
    - VMware


3. Name the provisioners supported by Vagrant out-of-the-box.
    - Chef
    - Puppet
    - Bash


4. Which is the default shared folder created on the guest machines by Vagrant?
    - /vagrant directory



5. Where on host machine is the guest shared folder mapped to?
    - /home/vagrant



6. Write a simple inline shell provisioners to command to copy an index.html on the folder where Vagrantfile resides to /var/www/html folder on the guest machine.
    - cp -R ~/vagrant/index.html /var/www/html



7. What is port mapping between Host and Guest machines and give an example
    - Port mapping is an application of network address translation (NAT) that redirects a communication request from one address and port number combination to another while the packets are traversing a network gateway, such as a router or firewall.


8. Using the reading reference “Node.js HTTP Module” above, create an infrastructure and configure it to run a NodeJS server available at port 80.
Clue: sudo apt install nodejs && sudo apt install npm
