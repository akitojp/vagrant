# vagrant
### vagrant up
```
vagrant init mybox
```

### box
```
vagrant package
vagrant box add <name> package.box
ls ~/.vagrant.d/boxes/
```

### Plugin
```
vagrant plugin install <plugin name>
vagrant plugin install sahara
vagrant plugin list
```

#### sahara
```
vagrant sandbox on
vagrant sandbox status
vagrant sandbox rollback
vagrant sandbox commit
vagrant sandbox off
```
