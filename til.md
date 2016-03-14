# TIL

## 2016-03-14

- Remove the OS X dock animation while hiding / unhiding:

```shell
$ defaults write com.apple.dock autohide-time-modifier -int 0; killall Dock
```
