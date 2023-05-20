Vagrant.configure("2") do |config|

  config.hostmanager.enabled = true
  config.hostmanager.manage_host = true


  config.vm.define "web01" do |web01|
    web01.vm.box = "generic/ubuntu2204"
    web01.vm.hostname = "web01"
  end

  config.vm.define "app01" do |app01|
    app01.vm.box = "centos/7"
    app01.vm.hostname = "app01"
  end

  config.vm.define "rmq01" do |rmq01|
    rmq01.vm.box = "centos/7"
    rmq01.vm.hostname = "rmq01"
  end

  config.vm.define "mc01" do |mc01|
    mc01.vm.box = "centos/7"
    mc01.vm.hostname = "mc01"
  end

  config.vm.define "db01" do |db01|
    db01.vm.box = "centos/7"
    db01.vm.hostname = "db01"
  end

end
