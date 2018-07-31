# _*_ mode: ruby _*_
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
	config.vm.box = "puphpet/ubuntu1404-x64"
	config.vm.network "private_network", ip: "192.168.35.25"
	config.vm.hostname = "server"
end	
config.vm.define "client" do |client|
	client.vm.box = "debian/jessie64"
	client.vm.network "private_network", ip: "192.168.27.56"
	client.vm.hostname = "client"
	
end
end
