Vagrant.configure("2") do |config|

  config.vm.box = "bento/ubuntu-22.04" 
  config.vm.box_download_options = {"ssl-no-revoke" => true}
  config.vm.network "private_network", ip: "192.168.50.4"
  
  config.vm.provider "virtualbox" do |vb|

     vb.memory = "5000"
	 vb.cpus = "2"
   end
   
end

  #config.vm.box_download_insecure = true
  #config.vm.boot_timeout = 60000
  #config.vm.boot_timeout = 600
  #config.vm.network "private_network"
  #config.vm.network "public_network", ip:"192.168.62.222"
  #config.vm.network "public_network", bridge: "Intel(R) Dual Band Wireless-AC 7265"
  #config.ssh.username = "vagrant"
  #config.ssh.password = "vagrant"
  #config.ssh.insert_key = false
	#vb.gui = true