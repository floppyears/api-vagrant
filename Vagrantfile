Vagrant.configure(2) do |config|
  config.vm.box = "CentOS-6.7_x64"
  config.vm.define "dropwizard-servers"

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook/dropwizard-servers-installation.yml"
  end
end
