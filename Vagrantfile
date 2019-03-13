Vagrant.configure("2") do |config|
  
  config.vm.box = "opentable/win-2012r2-standard-amd64-nocm"
  config.vm.network "forwarded_port", guest: 80, host: 4567

  config.vm.network "forwarded_port", guest: 3389, host: 3389
  
  config.vm.network "private_network", ip: "192.168.33.11"
  config.vm.network "public_network"

end
