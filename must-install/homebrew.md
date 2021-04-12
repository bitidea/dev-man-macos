# Homebrew

## 安装

### 🌍

https://brew.sh

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### 🇨🇳

https://juejin.im/post/5c738bacf265da2deb6aaf97

## 镜像

http://mirrors.ustc.edu.cn/help/brew.git.html

http://mirrors.ustc.edu.cn/help/homebrew-core.git.html

http://mirrors.ustc.edu.cn/help/homebrew-bottles.html

## 常用命令行工具

```bash
brew install \
  aria2 \
  gradle \
  maven \
  ncdu \
  netcat \
  neofetch \
  nmap \
  node \
  python \
  sqlite \
  tcpdump \
  telnet \
  tldr \
  tree \
  watch \
  wget \
  cmake
```

## Python 镜像

### 升级 pip 到最新版

```bash
pip3 install --upgrade pip -i https://pypi.douban.com/simple
```

### 设置镜像

```bash
pip3 config set global.index-url https://pypi.douban.com/simple
```

## jadx

Android 逆向工具，装完之后没有图标，只能在命令行运行

```bash
brew install jadx
```

## jmeter

压力测试工具，装完之后没有图标，只能在命令行运行

```bash
brew install jmeter
```

## ffmpeg

基本使用：http://www.ruanyifeng.com/blog/2020/01/ffmpeg.html

```bash
brew install ffmpeg
```

## Homebrew Cask 镜像

http://mirrors.ustc.edu.cn/help/homebrew-cask.git.html

## 升级所有 Cask 软件包

```bash
brew upgrade --cask --greedy
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

## iTerm

替代掉系统自带的 Terminal

```bash
brew install iterm
```

[点我进入「iTerm 2 配置」](../iterm2-config.md)

## iStat Menus

系统性能监控工具

```text
982092332@qq.com
GAWAE-FCWQ3-P8NYB-C7GF7-NEDRT-Q5DTB-MFZG6-6NEQC-CRMUD-8MZ2K-66SRB-SU8EW-EDLZ9-TGH3S-8SGA
```

```bash
brew install istat-menus
```

## eul

iStat Menus 的开源替代品，国人作者，[Apple Store Free](https://apps.apple.com/us/app/eul/id1537133867)

```bash
brew install eul
```

## Intel Power Gadget

有这个工具 iState 才能监控 CPU 频率

### ⚠️ 注意

Intel Power Gadget 有可能会让你的 Mac **无限重启**，在 iMac (Retina 4K, 21.5-inch, 2017) 上出现过这个问题，请慎重考虑是否安装

无限重启修复方法：启动时按住 `Shift` 键，进入安全模式，使用 Intel Power Gadget 自带的 `Uninstaller.pkg` 完全卸载

```bash
brew install intel-power-gadget
```

## Kap

录屏工具

```bash
brew install kap
```

## Keka

解压工具

```bash
brew install keka
```

## eZip

Keka 不能编辑压缩文件，eZip 可以

```bash
brew install ezip
```

## Mark Text

Markdown 编辑器，Typora 终结者

```bash
brew install mark-text
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

震惊：中国某九线城市网络聊天主播小学文凭月入百万

```bash
brew install obs
```

## Postman

API 调试工具

```bash
brew install postman
```

## Redis Desktop Manager

Redis GUI 工具

```bash
brew install another-redis-desktop-manager
```

## uPic

图床工具

```bash
brew install upic
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

## Charles

抓包工具

```text
https://zhile.io
48891cf209c6d32bf4
```

```bash
brew install charles
```

## Maccy

粘贴板增强

```bash
brew install maccy
```

## iSlide

PPT 制作工具

```bash
brew install islide
```

## V2ray

https://github.com/Homebrew/homebrew-core/blob/master/Formula/v2ray.rb

`_______，_______。`

```bash
brew install v2ray
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

## bob

翻译插件，建议[申请各大平台的免费私人 Key ](https://ripperhe.gitee.io/bob/#/general/quickstart/service?id=%e7%a7%81%e4%ba%ba%e7%a7%98%e9%92%a5)使用

```bash
brew install bob
```
