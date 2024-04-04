# 🇨🇳 安装 rustup

## Rustup Mirror

```bash
export RUSTUP_DIST_SERVER="https://rsproxy.cn"
export RUSTUP_UPDATE_ROOT="https://rsproxy.cn/rustup"
```

```bash
curl --proto '=https' --tlsv1.2 -sSf https://rsproxy.cn/rustup-init.sh | sh
```

## crates.io Mirror

```bash
vim ~/.cargo/config
```

```toml
[source.crates-io]
registry = "sparse+https://rsproxy.cn/index/"
[net]
git-fetch-with-cli = true
```
