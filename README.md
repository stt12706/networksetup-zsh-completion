# networksetup-zsh-completion
zsh-completion for networksetup, the configuration tool for network settings in macOS

This is an incomplete zsh-completion for networksetup.

The only supported completion are basic commands, commands with one argument ("hardwareport or device name", "device name", and "networkservice"), and switch options ("on" and "off")

For example,

[Just basic commands]
```
$ networksetup -listallhardwareports
$ networksetup -printcommands
$ networksetup -help
```

[Commands with one argument]
```
$ networksetup -getmacaddress <hardwareport or device name>
$ networksetup -getinfo <networkservice>
```

[Commands with switch option]
```
$ networksetup -setairportpower <device name> <on/off>
$ networksetup -setnetworkserviceenabled <networkservice> <on/off>
```
