Vagrant.configure("2") do |config|

  config.vm.define "controlbox" do |controlbox|
    controlbox.vm.box = "centos/7"
    controlbox.vm.hostname = "controlbox"
    controlbox.vm.network "private_network", ip: "192.168.5.2"
  end

  config.vm.define "web11" do |web11|
    web11.vm.box = "centos/7"
    web11.vm.hostname = "web11"
    web11.vm.network "private_network", ip: "192.168.5.3"
  end

  config.vm.define "web12" do |web12|
    web12.vm.box = "centos/7"
    web12.vm.hostname = "web12"
    web12.vm.network "private_network", ip: "192.168.5.4"
  end

  config.vm.define "web13" do |web13|
    web13.vm.box = "ubuntu/xenial64"
    web13.vm.hostname = "web13"
    web13.vm.network "private_network", ip: "192.168.5.5"
  end

end
