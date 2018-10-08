# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "lnx-rhel"
#  config.vm.box_url = "http://atf.intranet.bb.com.br/artifactory/bb-vagrant-local/lnx/rhel/lnx-rhel.json"

  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
  end

  config.vm.define "rhel" do |m|
    m.vm.network "private_network", ip: "172.17.177.51"
  end
end
