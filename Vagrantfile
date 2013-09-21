# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant::Config.run do |config|

  config.vm.customize ["modifyvm", :id, "--memory", 3072]

  config.vm.box = "centos-64-x64"
  config.vm.box_url = "http://puppet-vagrant-boxes.puppetlabs.com/centos-64-x64-vbox4210.box"
  config.vm.network :hostonly, "12.0.0.31"

end
