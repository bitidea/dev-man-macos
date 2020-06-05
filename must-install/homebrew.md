# Homebrew

## 安装

### 🌍

https://brew.sh

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
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
  wget
```

## openjdk@11

```bash
brew install openjdk@11
```

### 配置环境变量

```bash
echo 'export PATH="/usr/local/opt/openjdk@11/bin:$PATH"' >> ~/.zshrc
```

```bash
echo 'export CPPFLAGS="-I/usr/local/opt/openjdk@11/include"' >> ~/.zshrc
```

### 配置 IDEA JDK

1. 打开 IDEA JDK 配置窗口

2. 使用组合键 `shift` + `command` + `.` 显示隐藏文件夹

3. 选到 `/usr/local/opt/openjdk@11/libexec/openjdk.jdk`

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
