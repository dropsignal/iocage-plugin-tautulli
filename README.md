# iocage-plugin-tautulli
Unofficial [Tautulli](https://github.com/Tautulli/Tautulli) iocage plugin for [FreeNAS](http://www.freenas.org) and [TrueNAS](https://www.truenas.com)

# Installing Plugins

## Using Local File
```
iocage fetch -P /the/path/to/tautulli.json vnet="on" ip4_addr="vnet0|192.168.0.100" -n tautulli
```

## Pulling from Internet
```
iocage fetch --plugins --name "tautulli" ip4_addr="igb0|192.168.0.91"
```
