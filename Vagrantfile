# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"
#  config.vm.box = "centos/7"

  config.vm.network "public_network", ip: "192.168.1.22"

  config.vm.provider "virtualbox" do |vb|
     vb.gui = true
     vb.memory = "1024"
   end
end
