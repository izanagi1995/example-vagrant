# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "vagrant-exampke"
  config.vm.define "vagrant-example"
  config.vm.hostname = "vagrant-example"

  config.vm.provider "virtualbox" do |vb|
     vb.memory = "512"
     vb.name = "vagrant-example"
  end

  # install docker, start it.
  config.vm.provision "shell", inline: <<-SHELL
    echo "Yo! This box is running well!"
  SHELL

end

