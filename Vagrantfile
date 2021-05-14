Vagrant.configure(2) do |config|

config.vm.box = "geerlingguy/centos7"
#config.vm.provision :docker 
 config.vm.define "server1" do |server1|
      server1.vm.network  "public_network",bridge:"enp0s8", ip: "192.168.1.160"
      server1.vm.hostname = "server1"  
      server1.vm.provider "virtualbox" do |server1|
         server1.memory = "1200"
    

      end
  end

  
 config.vm.define "server2" do |server2|
     server2.vm.network "public_network",bridge:"enp0s8", ip: "192.168.1.161"
     server2.vm.hostname = "server2"  
     server2.vm.provider "virtualbox" do |server2|
          server2.memory = "1200"


     end
 end


 config.vm.define "server3" do |server3|
    server3.vm.network "public_network",bridge:"enp0s8", ip: "192.168.1.163"
     server3.vm.hostname = "server3"
     server3.vm.provider "virtualbox" do |server3|
         server3.memory = "1200"
end
end




end 
