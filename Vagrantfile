# -*- mode: ruby -*-
# vi: set ft=ruby :

# See README.md for details

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.box = "centos65-base"

  config.vm.define "linuxtest" do |linuxtest|
  
    linuxtest.vm.hostname = "linuxtest"
  
    linuxtest.vm.network "private_network", ip: "172.31.0.201"
  
  end
  
end
