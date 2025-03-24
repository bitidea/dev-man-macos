# 清除 DNS 缓存

[How to Flush DNS on Mac – MacOS Clear DNS Cache](https://www.freecodecamp.org/news/how-to-flush-dns-on-mac-macos-clear-dns-cache)

| MACOS VERSION                | COMMAND                                                         |
| ---------------------------- | --------------------------------------------------------------- |
| macOS 12 (Monterey)          | `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder` |
| macOS 11 (Big Sur)           | `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder` |
| macOS 10.15 (Catalina)       | `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder` |
| macOS 10.14 (Mojave)         | `sudo killall -HUP mDNSResponder`                               |
| macOS 10.13 (High Sierra)    | `sudo killall -HUP mDNSResponder`                               |
| macOS 10.12 (Sierra)         | `sudo killall -HUP mDNSResponder`                               |
| OS X 10.11 (El Capitan)      | `sudo killall -HUP mDNSResponder`                               |
| OS X 10.10 (Yosemite)        | `sudo discoveryutil udnsflushcaches`                            |
| OS X 10.9 (Mavericks)        | `sudo killall -HUP mDNSResponder`                               |
| OS X 10.8 (Mountain Lion)    | `sudo killall -HUP mDNSResponder`                               |
| Mac OS X 10.7 (Lion)         | `sudo killall -HUP mDNSResponder`                               |
| Mac OS X 10.6 (Snow Leopard) | `sudo dscacheutil -flushcache`                                  |
| Mac OS X 10.5 (Leopard)      | `sudo lookupd -flushcache`                                      |
| Mac OS X 10.4 (Tiger)        | `lookupd -flushcache`                                           |
