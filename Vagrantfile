Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
  config.vm.synced_folder "app/", "/var/www/app",
    create: true, owner: "vagrant", group: "vagrant",
    id: "app"
end
