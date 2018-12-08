Vagrant.configure("2") do |config|
  config.vm.box = "bento/centos-7.4"

  config.vm.define "node1" do |node|
    node.vm.network :private_network, ip: "192.168.10.11"
  end

  config.vm.define "node2" do |node|
    node.vm.network :private_network, ip: "192.168.10.12"
  end
end
