# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  # Image Ubuntu Server 22.04 LTS
  config.vm.box = "ubuntu/jammy64"

  # Réseau privé avec IP fixe
  config.vm.network "private_network", ip: "192.168.56.50"

  # Configuration VirtualBox
  config.vm.provider "virtualbox" do |vb|
    vb.name = "VM-Ubuntu-Mggt1103"
    vb.memory = "1024"   # 1 Go RAM
    vb.cpus = 1          # 1 CPU
  end

end