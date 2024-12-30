# Homebrew

[首次安装 + 镜像配置](https://mirrors.tuna.tsinghua.edu.cn/help/homebrew/)

## 常用命令行工具

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

## jadx

Android 逆向工具，装完之后没有图标，在命令行启动

```bash
brew install jadx
```

## jmeter

压力测试工具，装完之后没有图标，在命令行启动

```bash
brew install jmeter
```

## ffmpeg

[基本使用教程](http://www.ruanyifeng.com/blog/2020/01/ffmpeg.html)

```bash
brew install ffmpeg
```

## adoptopenjdk

JDK

```bash
brew tap AdoptOpenJDK/openjdk
```

```bash
brew install adoptopenjdk11
```

## Fork

Git GUI 工具

```bash
brew install fork
```

## Hack Nerd Font

终端唯一指定字体

```bash
brew tap homebrew/cask-fonts
```

```bash
brew install font-hack-nerd-font
```

## IINA

视频播放器

```bash
brew install iina
```

## iTerm2

替代掉系统自带的 Terminal

```bash
brew install iterm2
```

[「iTerm 2 配置」传送门](../software-config/iterm2-config.md)

## iStat Menus（需要注册码）

系统性能监控工具

```bash
brew install istat-menus
```

## Intel Power Gadget

有这个工具 iState 才能监控 CPU 频率

```bash
brew install intel-power-gadget
```

### ⚠️ 注意

Intel Power Gadget 有可能会让你的 Mac **无限重启**，在 iMac (Retina 4K, 21.5-inch, 2017) 上出现过这个问题，请慎重考虑是否安装

无限重启修复方法：启动时按住 `Shift` 键，进入安全模式，使用 Intel Power Gadget 自带的 `Uninstaller.pkg` 完全卸载

## Keka

解压工具

```bash
brew install keka
```

## Motrix

下载工具，支持磁力

```bash
brew install motrix
```

## Mounty

NTFS 读写工具

```bash
brew install mounty
```

## Mos

鼠标行为调教工具

```bash
brew install mos
```

## OBS

推流 & 录屏工具

```bash
brew install obs
```

## Another Redis Desktop Manager

Redis GUI 工具

```bash
brew install another-redis-desktop-manager
```

## Wireshark

抓包工具

```bash
brew install wireshark
```

## Sloth

`lsof` GUI 工具

```bash
brew install sloth
```

## qBittorrent Enhanced

qBittorrent 增强版，自动 Ban 吸血 IP

```bash
brew install c0re100-qbittorrent
```

## Charles（需要注册码）

抓包工具

```bash
brew install charles
```

## Maccy

粘贴板增强

```bash
brew install maccy
```

## balenaEtcher

镜像烧录工具

```bash
brew install balenaetcher
```

## jd-gui

逆向工具，反编译 JAR

```bash
brew install jd-gui
```

## Beekeeper Studio

SQL client for MySQL, Postgres, SQLite, SQL Server, and more.

```bash
brew install beekeeper-studio
```

## SwitchHosts

Switch hosts quickly!

https://github.com/oldj/SwitchHosts

```bash
brew install switchhosts
```
