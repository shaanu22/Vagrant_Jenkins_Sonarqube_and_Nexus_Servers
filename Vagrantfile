Vagrant.configure("2") do |config|

# config.vm.define "jenkins" do |jenkins|
#   jenkins.vm.box = "ubuntu/focal64"
#   jenkins.vm.network "public_network"
  
#   jenkins.vm.provider "virtualbox" do |vb|
#     vb.name="jenkins"
#     vb.gui = false
#     vb.cpus = 2
#     vb.memory = "2096"
#   end
  
#   jenkins.vm.provision "shell" do |shell|
#     shell.path = "jenkins.sh"
#   end
# end

config.vm.define "nexus" do |nexus|
  nexus.vm.box = "generic/centos7"
  nexus.vm.network "public_network"

  nexus.vm.provider "virtualbox" do |vb2|
    vb2.name="nexus"
    vb2.gui = false
    vb2.cpus = 2
    vb2.memory = "4096"
  end

  nexus.vm.provision "shell" do |shell|
    shell.path = "nexus-setup.sh"
  end
end
config.vm.define "sonar" do |sonar|
  sonar.vm.box = "ubuntu/focal64"
  sonar.vm.network "public_network"

  sonar.vm.provider "virtualbox" do |vb|
    vb.name="sonar"
    vb.gui = false
    vb.cpus = 4
    vb.memory = "3096"
  end

  sonar.vm.provision "shell" do |shell|
    shell.path = "sonar-setup.sh"
  end
end
end
