# -*- mode: ruby -*-
# vi: set ft=ruby :

ENV['VAGRANT_DEFAULT_PROVIDER'] = 'libvirt'

Vagrant.configure("2") do |config|
  config.vm.box = "coreos_production_vagrant_virtualbox"
  config.vm.provider :libvirt do |v|
    v.cpus = 2
    v.memory = 2048
  end
end
