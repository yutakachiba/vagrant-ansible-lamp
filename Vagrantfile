# -*- coding: utf-8 -*-
# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.box = "CentOS65"
  config.vm.box_url = "https://github.com/2creatives/vagrant-centos/releases/download/v6.5.3/centos65-x86_64-20140116.box"

  config.vm.network "private_network", ip: "192.168.33.101"
  config.vm.network "forwarded_port", guest: 22, host: 2210
#  config.vm.network :public_network, :bridge => "en0: Wi-Fi (AirPort)"
  
#  config.vm.synced_folder ".", "/var/www/vhosts", :create => true, :owner => 'vagrant', :group => 'vagrant', :mount_options => ['dmode=777', 'fmode=755']

#  config.ssh.pty = true

#  config.vm.provision :ansible do |ansible|
#    ansible.playbook = "ansible/playbook.yml"
#    ansible.inventory_path = "ansible/inventories/dev"
#  end
end
