Vagrant.configure("2") do |config|
  config.vm.provider "docker" do |d|
    d.image = "ubuntu-ssh"
    d.has_ssh = true
    d.remains_running = true
  end
end
