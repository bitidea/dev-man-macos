# macOS Environment Variables

## Environment Variables

### 查看所有环境变量

```bash
env
```

### 设置一个 Variable

```bash
# 通过可执行文件设置
export JAVA_HOME=$(/path/to/JDK-exec-directory)

# 通过目录设置
export JAVA_HOME=/path/to/JDK-installed-directory
```

### 打印某个已设置的 Variable

```bash
echo $JAVA_HOME
```

## PATH

### 查看当前 PATH

```bash
echo $PATH
```

### 修复损坏的 PATH (恢复默认 PATH)

```bash
export PATH="/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin"
```

### 添加自己的 PATH

```bash
export PATH="${PATH}:你的新目录"
```

### 刷新终端配置

```bash
source ~/.zshrc
```

## 常见的配置文件

- /etc/paths (全局建议修改这个文件)

编辑 paths, 将环境变量添加到 paths 文件中, 一行一个路径

tips: 输入环境变量时, 直接拖动文件夹到 Terminal 里就可以了

- /etc/profile (建议不修改这个文件)

全局（公有）配置，不管是哪个用户，登录时都会读取该文件

- /etc/bashrc (一般在这个文件中添加系统级环境变量)

全局（公有）配置，bash shell 执行时，不管是何种方式，都会读取此文件

- .profile (系统的每个用户设置环境信息)

当用户第一次登录时，该文件被执行，并从 /etc/profile.d 目录的配置文件中搜集 shell 设置

tips: 修改 /etc/profile 必须重启才会生效, 此修改对每个用户都生效

- .bashrc (每一个运行 bash shell 的用户执行此文件)

当 bash shell 被打开时, 该文件被读取

tips: 对所有的 bash 用户生效, 修改后启动一个新的 bash shell 即可

- .bash_profile (用于你的 bash shell 的 bash 信息)

当登录时以及每次打开新的 bash shell 时, 该文件被读取, 每个用户的家目录都有一个 .bashrc 文件

tips: 需要需要重启才会生效, /etc/profile 对所有用户生效, ~/.bash_profile 只对当前用户生效

- .zshrc (每一个运行 zsh shell 的用户执行此文件)

当 zsh shell 被打开时, 该文件被读取

tips: 对所有的 zsh 用户生效, 修改后启动一个新的 zsh shell 即可

- .zsh_profile (用于你的 zsh shell 的 zsh 信息)

当登录时以及每次打开新的 zsh shell 时, 该文件被读取, 每个用户的家目录都有一个 .zshrc 文件

tips: 需要需要重启才会生效, /etc/profile 对所有用户生效, ~/.zsh_profile 只对当前用户生效

- .netrc (用于完成常见协议的权限验证)
  当你访问 git、ftp 等常见协议的时候自动验证账号密码
  tips: 有些时候不能直接用账号密码，而是要用 token

.netrc 示例

```
machine github.com
login charles
password password
```
