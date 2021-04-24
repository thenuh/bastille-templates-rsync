## Status
not implemeted

## rsync
Bastille Template for an chrooted rsync only container

## Bootstrap
```shell
bastille bootstrap https://gitlab.com/thenuh/bastille-templates-rsync
```

## Usage
```shell
bastille template TARGET thenuh/bastille-templates-rsync\
--arg ssh_username=< some users name>\
--arg ssh_from_ip=< the ip the user connects from >\
--arg ssh_port=< the port that shall be redirected into the jail, and the port sshd listens on>\
--arg ssh_pwd=< in case you need to set a password for the user>\
--arg ssh_key=<ed25519 AAA... someuser@this>
```
