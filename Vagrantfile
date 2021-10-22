Vagrant.configure("2") do |config|
  config.vm.synced_folder '.', '/vagrant', disabled: true
  config.vm.provider :libvirt do |libvirt|
    libvirt.driver = "kvm"
    libvirt.nic_model_type = "e1000"
    libvirt.disk_bus = 'ide'
    libvirt.memory = '2048m'
  end
end
