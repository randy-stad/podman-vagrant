# -*- mode: ruby -*-
# vi: set ft=ruby :

ENV['VAGRANT_NO_PARALLEL'] = 'yes'

Vagrant.configure("2") do |config|
  # start with centos 8
  config.vm.define "podman"
  config.vm.hostname = "podman"
  config.vm.box = "centos/8"
  # provision podman
  config.vm.provision "shell", path: 'provision-podman.sh'
end