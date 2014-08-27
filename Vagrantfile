# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"
Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "insaneworks/centos"
  end
  config.vm.provision :shell, inline: "/vagrant/CentOS70.sh && cat centos70.tar.xz > /vagrant/centos70.tar.xz"
end
