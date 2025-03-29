# Homebrew

[首次安装 + 镜像配置](https://mirrors.ustc.edu.cn/help/brew.git.html)

## macOS 基础
```
xcode-select --install
```

## 语言环境

### Rust
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

### Go
```
brew install go
```

### Java
```bash
brew install --cask zulu@21
```

## CLI

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
  wget \
  topgrade \
  ffmpeg \
  mitmproxy
```

## GUI
### Shottr
截图工具
```
brew install --cask shottr
```

### Fork

Git GUI 工具

```bash
brew install fork
```

### IINA

视频播放器

```bash
brew install iina
```

### Easydict
翻译工具，替代 Bob
```
brew install --cask easydict
```

### iStat Menus（需要注册码）

系统性能监控工具

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

推流 & 录屏工具

```bash
brew install obs
```

### qBittorrent Enhanced

qBittorrent 增强版，自动 Ban 吸血 IP

```bash
brew install c0re100-qbittorrent
```

### balenaEtcher

镜像烧录工具

```bash
brew install balenaetcher
```

## 数据库管理
### Another Redis Desktop Manager

Redis GUI 工具

```bash
brew install another-redis-desktop-manager
```

### Beekeeper Studio

SQL client for MySQL, Postgres, SQLite, SQL Server, and more.

```bash
brew install beekeeper-studio
```

## 系统增强
### Pearcleaner
卸载清理
```
brew install pearcleaner
```

### Mos

鼠标行为调教工具

```bash
brew install mos
```

### Maccy

粘贴板增强

```bash
brew install maccy
```

### Keka

解压工具

```bash
brew install keka
```

### Mounty

NTFS 读写工具

```bash
brew install mounty
```

### Sloth

`lsof` GUI 工具

```bash
brew install sloth
```

### iTerm2

替代掉系统自带的 Terminal

```bash
brew install iterm2
```

### SwitchHosts

快速切换 HOST 文件

```bash
brew install switchhosts
```

### Open In Termina
鼠标右键在此处打开控制台
```
brew install --cask openinterminal
```


## 调试
### mitmproxy

```
brew install --cask mitmproxy
```

### whistle

```
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

压力测试工具，装完之后没有图标，在命令行启动

```bash
brew install jmeter
```

## 逆向
### jd-gui

逆向工具，反编译 JAR

```bash
brew install jd-gui
```

### jadx

Android 逆向工具，装完之后没有图标，在命令行启动

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