Vagrant.configure("2") do |config|
    config.vm.box = "centos/7"
    config.vm.hostname = "centos.local"
    config.vm.provision :shell, path: "bootstrap.sh"
    config.vm.network "private_network", ip: "192.168.100.73"
    # config.vm.network :forwarded_port, guest: 80, host: 4567
     config.vm.synced_folder ".", "/vagrant", type: "virtualbox"

     #plugin
     config.hostsupdater.aliases = ["centos73"]
end
