# 使用 Touch ID 认证 sudo

视频：[https://www.bilibili.com/video/BV19e411M7au](https://www.bilibili.com/video/BV19e411M7au)

```bash
cd /etc/pam.d
```

```bash
sudo vim sudo
```

```bash
auth sufficient pam_tid.so
```

```bash
:x!
```
