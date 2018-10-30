Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.network "forwarded_port", guest: 80, host: 80
  config.vm.network "forwarded_port", guest: 3306, host: 3306
  config.vm.network "private_network", ip: "10.0.0.10"
  config.vm.provider "virtualbox" do |v|
     v.memory = 2048
     v.cpus = 2
  end
  end
