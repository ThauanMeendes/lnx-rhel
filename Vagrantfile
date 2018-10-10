# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "lnx-rhel"
#  config.vm.box_url = "http://www.exemplo.com"

  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
  end

  config.vm.define "rhel" do |m|
    m.vm.network "private_network", ip: "xxx.xxx.xxx.xx"
  end
end
