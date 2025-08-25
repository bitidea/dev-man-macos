# Launchpad 重置

before macOS Sequoia (15)

```bash
defaults write com.apple.dock ResetLaunchPad -bool true && killall Dock
```

after macOS Sequoia (15)

```bash
sudo find 2>/dev/null /private/var/folders/ -type d -name com.apple.dock.launchpad -exec rm -rf {} +; killall Dock
```
