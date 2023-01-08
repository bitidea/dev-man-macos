# Audacity 卡顿修复

`Applications` -> `Audacity.app` -> 右键 -> `Show Package Contents`

`Contents` -> 用文本编辑器打开 `Info.plist`

将

```xml
<key>NSHighResolutionCapable</key>
<true/>
```

改为

```xml
<key>NSHighResolutionCapable</key>
<false/>
```

保存重启软件
