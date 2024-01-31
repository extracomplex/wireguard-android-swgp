# Android GUI for [WireGuard](https://www.wireguard.com/)

This is an Android GUI for [WireGuard](https://www.wireguard.com/). It uses the non-root [userspace implementation](https://git.zx2c4.com/wireguard-go/about/). The [Simple Wireguard Proxy](https://github.com/database64128/swgp-go) support is built-in.



## Building

```
$ git clone --recurse-submodules git clone --recurse-submodules https://git.zx2c4.com/wireguard-android

$ cd wireguard-android
$ ./gradlew assembleRelease
```

macOS users may need [flock(1)](https://github.com/discoteq/flock).


## Translating

Please help us translate the app into several languages on [our translation platform](https://crowdin.com/project/WireGuard).
