# vagrant
## vagrant up
```
vagrant init mybox
```

## box
```
vagrant package
vagrant box add <name> package.box
ls ~/.vagrant.d/boxes/
```

## Snapshots
```
# List snapshots
vagrant snapshot list

# Create a snapshot
vagrant snapshot push

# Restore snapshot
vagrant snapshot pop

# Create snapshot (specify snapshot name)
vagrant snapshot save [name]

# Restore snapshot (specify snapshot name)
vagrant snapshot restore [name]

# Delete snapshot (specify snapshot name)
vagrant snapshot delete [name]

# Storage directory of the snapshot
~/VirtualBox VMs/<vm_name>/Snapshots/
```

# Plugin
```
# Installing a plugin from a known gem source
$ vagrant plugin install my-plugin

# Installing a plugin from a local file source
$ vagrant plugin install /path/to/my-plugin.gem

# Uninstall
$ vagrant plugin uninstall my-plugin

```
