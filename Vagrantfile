# orc8r box

Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/focal64"
  config.vm.box_check_update = false

  # config.vm.network "public_network", bridge: "wlp0s20f3"
  config.vm.network "private_network", type: "dhcp"
  # config.vm.network "private_network", ip: "172.28.128.10"

  config.vm.provider "virtualbox" do |v|

    # v.memory = 4096
    v.memory = 8192
    v.cpus = 4

  end

end
