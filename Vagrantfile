Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.hostname = 'docker'
  config.vm.provision "shell", path: "provision.sh"  
end
