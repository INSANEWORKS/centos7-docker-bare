# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"
Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "insaneworks/centos7"
  config.vm.provision :shell, inline: <<-EOS
    yum install -y docker
    service docker start
    /vagrant/mkimage-yum.sh insaneworks/centos7
  EOS
end
