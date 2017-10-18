# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.provision "shell", inline: <<-SHELL
    apt-get update -y
    apt-get install -y qemu qemu-user-static binfmt-support
  SHELL
end
