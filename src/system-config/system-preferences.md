# 系统首选项调整

[https://www.robinwieruch.de/mac-setup-web-development](https://www.robinwieruch.de/mac-setup-web-development)

```bash
# 截图格式设置为更小的 jpg，而不是 png
defaults write com.apple.screencapture type jpg

# 打开新文件时，不要打开以前预览的文件（例如 PDF）
defaults write com.apple.Preview ApplePersistenceIgnoreState YES

# 显示 Library 文件夹
chflags nohidden ~/Library

# 显示隐藏的文件
defaults write com.apple.finder AppleShowAllFiles YES

# Finder 显示路径栏
defaults write com.apple.finder ShowPathbar -bool true

# Finder 显示状态栏
defaults write com.apple.finder ShowStatusBar -bool true

killall Finder;
```
