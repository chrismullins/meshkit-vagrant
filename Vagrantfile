Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/precise64"
  config.vm.define 'machine1' do |machine|
    machine.vm.hostname = 'machine1'
    machine.vm.provision :ansible do |ansible|
      ansible.playbook = "provisioning/playbook.yml"
    end
  end
end
