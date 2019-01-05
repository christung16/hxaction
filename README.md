deploy vcenter 6.5 has to set correct NTP and DNS. Otherwise, it may fail to install the RPM modules.
Also remind the root expiry date.

Set the variables in common/vars/main.yml

examples:

esxi_hostname: '<ip>'
esxi_password: 'xxxxxx'
esxi_username: 'root'
esxi_network: 'VM Network'
esxi_datastore: 'Datastore_Backup'
vc_name: 'vcenter-6.5.0'
vc_ip: '<vcenter ip>'
vc_prefix: '24'
vc_gateway: '<gw ip>'
vc_dns: '<dns ip>'
vc_ntp: '<ntp ip>'
vc_password: '<vcenter password>'
vcsa_iso: '<VCSA ISO>'


