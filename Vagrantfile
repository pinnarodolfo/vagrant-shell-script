Vagrant.configure("2") do |config|
	config.vm.provider "virtualbox" do |projeto2|
	projeto2.name = "segundoprojeto"
	config.vm.provision "shell" , path: "script.sh"
  end
	config.vm.box = "ubuntu/focal64"

end
