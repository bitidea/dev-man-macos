# 错误
UNABLE_TO_GET_ISSUER_CERT_LOCALLY

# 原因
用 brew 安装 ca-certificates openssl 会更新系统的 CA，更新出错时会导致 SSL 校验失败。

# 解决方案
```bash
brew reinstall ca-certificates openssl@3 node
```