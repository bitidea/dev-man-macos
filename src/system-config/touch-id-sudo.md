# 使用 Touch ID 认证 sudo

```bash
cd /etc/pam.d
```

```bash
sudo vim sudo
```

写在第一行

```bash
auth sufficient pam_tid.so
```

```bash
:x!
```
