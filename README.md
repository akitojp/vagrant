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

# Plugin
## Sahara
```
# sandbox mode on
$ vagrant sandbox on

# Rollback
$ vagrant sandbox rollback

# commit
$ vagrant sandbox commit

# sandbox mode off
$ vagrant sandbox off

# sandbox status
$ vagrant sandbox status
```

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
