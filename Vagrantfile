Vagrant.configure('2') do |config|
  config.vm.define 'postres_primary' do |acs|
    acs.vm.box = 'ubuntu/trusty64'
    acs.vm.hostname = 'pp'
    acs.vm.network  'private_network', ip: '192.168.100.10'
  end

  config.vm.define 'postres_standby_1' do |acs|
    acs.vm.box = 'ubuntu/trusty64'
    acs.vm.hostname = 'ps1'
    acs.vm.network  'private_network', ip: '192.168.100.20'
  end

  config.vm.define 'postres_standby_2' do |acs|
    acs.vm.box = 'ubuntu/trusty64'
    acs.vm.hostname = 'ps2'
    acs.vm.network  'private_network', ip: '192.168.100.30'
  end
end
