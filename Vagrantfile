# -*- mode: ruby -*-
# vi: set ft=ruby :

# TOADD in :bridge => 'en5: Ethernet Thunderbolt'
# TOADD in :bridge => 'en0: Wi-Fi (AirPort)'
# 1) en5: Ethernet Thunderbolt
# 2) en0: Wi-Fi (AirPort)

Vagrant.configure(2) do |config|
  config.vm.define "master1" do |db|
    db.vm.box = "ubuntu/trusty64"
    db.vm.network "public_network", ip:"192.168.1.211"
  end
  config.vm.define "master2" do |db|
    db.vm.box = "ubuntu/trusty64"
    db.vm.network "public_network", ip:"192.168.1.212"
  end
  config.vm.define "master3" do |db|
    db.vm.box = "ubuntu/trusty64"
    db.vm.network "public_network", ip:"192.168.1.213"
  end
  config.vm.define "slave1" do |db|
    db.vm.box = "ubuntu/trusty64"
    db.vm.network "public_network", ip:"192.168.1.214"
  end
  config.vm.define "slave2" do |db|
    db.vm.box = "ubuntu/trusty64"
    db.vm.network "public_network", ip:"192.168.1.215"
  end
  config.vm.define "slave3" do |db|
    db.vm.box = "ubuntu/trusty64"
    db.vm.network "public_network", ip:"192.168.1.216"
  end
end