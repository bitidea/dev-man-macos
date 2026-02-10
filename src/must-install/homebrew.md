# Homebrew

[首次安装 + 镜像配置](https://mirrors.ustc.edu.cn/help/brew.git.html)

## macOS 基础

```bash
xcode-select --install
```

## 语言环境

### 安装 mise

```bash
curl https://mise.run | sh
```

### 安装 Rust

```bash
mise use -g rust
```

### 安装 Go

```bash
mise use -g go
```

### 安装 Java

```bash
mise use -g java@temurin-25
```

### 安装 Python

```bash
mise use -g python@3.14
```

### 安装 Node

```bash
mise use -g node@24
```

## 命令行工具

### 常用

```bash
brew install \
  aria2 \
  cmake \
  ncdu \
  sqlite \
  telnet \
  tldr \
  tree \
  watch \
  wget
```

### topgrade

一键更新开发环境

```bash
brew install topgrade
topgrade -y -c --no-retry --disable system
```

### ffmpeg

视频处理

```bash
brew install ffmpeg
```

## 常用软件

### Shottr

截图

```bash
brew install --cask shottr
```

### Fork

Git GUI

```bash
brew install fork
```

### IINA

视频播放器

```bash
brew install iina
```

### Easydict

翻译

```bash
brew install --cask easydict
```

### iStat Menus（需要注册码）

系统性能监控

```bash
brew install istat-menus
```

监控 CPU 频率需要安装 Intel Power Gadget

```bash
brew install intel-power-gadget
```

`注意`：Intel Power Gadget 有可能会让你的 Mac **无限重启**，在 iMac (Retina 4K, 21.5-inch, 2017) 上出现过这个问题，请慎重考虑是否安装。

无限重启修复方法：启动时按住 **Shift** 键，进入安全模式，使用 Intel Power Gadget 自带的 **Uninstaller.pkg** 完全卸载

### OBS

推流 & 录屏

```bash
brew install obs
```

### qBittorrent Enhanced

qBittorrent 增强版，自动 Ban 吸血 IP

```bash
brew install c0re100-qbittorrent
```

### balenaEtcher

镜像烧录

```bash
brew install balenaetcher
```

## 数据库管理

### Another Redis Desktop Manager

Redis

```bash
brew install another-redis-desktop-manager
```

## 系统增强

### Pearcleaner

卸载清理

```bash
brew install pearcleaner
```

### Mos

鼠标行为调教

```bash
brew install mos
```

### Maccy

粘贴板增强

```bash
brew install maccy
```

### Keka

解压

```bash
brew install keka
```

### Mounty

NTFS 读写

```bash
brew install mounty
```

### Sloth

`lsof` GUI

```bash
brew install sloth
```

### Ghostty

新一代 Terminal

```bash
brew install --cask ghostty
```

### SwitchHosts

快速切换 HOST 文件

```bash
brew install switchhosts
```

### Open In Termina

鼠标右键在此处打开控制台

```bash
brew install --cask openinterminal
```

## 调试

### mitmproxy

```bash
brew install mitmproxy
```

### whistle

```bash
brew install whistle
```

### Charles（需要注册码）

```bash
brew install charles
```

### Wireshark

```bash
brew install wireshark
```

### jmeter

压力测试，装完之后没有图标，在命令行启动

```bash
brew install jmeter
```

## 逆向

### jd-gui

逆向，反编译 JAR

```bash
brew install jd-gui
```

### jadx

Android 逆向，装完之后没有图标，在命令行启动

```bash
brew install jadx
```

## 字体

### Hack Nerd Font

终端唯一指定字体

```bash
brew tap homebrew/cask-fonts
```

```bash
brew install font-hack-nerd-font
```

## 相关文章

- [ffmpeg 基本使用教程](http://www.ruanyifeng.com/blog/2020/01/ffmpeg.html)
- [通过 mitmproxy 修改 response](https://blog.d8s.fun/posts/go-retryablehttp)
- [Charles 注册码生成](https://www.zzzmode.com/mytools/charles)
- [iTerm 2 配置」传送门](../software-config/iterm2-config.md)
- [topgrade 仓库](https://github.com/topgrade-rs/topgrade)
