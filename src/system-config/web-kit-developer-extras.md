# macOS 开启 WebKit 审查元素

[https://blog.jim-nielsen.com/2022/inspecting-web-views-in-macos/](https://blog.jim-nielsen.com/2022/inspecting-web-views-in-macos/)

```bash
defaults write NSGlobalDomain WebKitDeveloperExtras -bool true
defaults write -g WebKitDeveloperExtras -bool YES
```
