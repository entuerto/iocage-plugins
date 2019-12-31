# iocage-plugins
Manifests for my personal FreeNAS plugins

## How to install a plugin
### Fetch plugin configuration
```
fetch https://raw.githubusercontent.com/entuerto/iocage-plugins/master/plugin_name.json
```
### Install plugin
```
iocage fetch --plugin-name plugin_name.json -n jail_name dhcp=on vnet=on bpf=yes
iocage fetch --plugin-name plugin_name.json -n jail_name vnet=on nat=on
```

