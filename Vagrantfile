# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.box = "stackroute/html"
  config.vm.box_url = "http://10.219.85.67/vagrant/boxes/stackroute-html.box"

  # Map the guest os port 8080 to host os port 8080
  config.vm.network "forwarded_port", guest: 8080, host: 9095
  config.vm.network "forwarded_port", guest: 9080, host: 9091


end
