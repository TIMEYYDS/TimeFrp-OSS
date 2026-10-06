# TimeFrp-OSS · 时光FRP 客户端分发仓库

内网穿透面板「时光FRP」（frp.acesb.top）官方客户端下载分发仓库。

## 客户端（内置 frpc，免配置自动同步隧道）

| 平台 | 文件 |
|---|---|
| Windows 64位 | shiguangfrp-windows-amd64.exe |
| Windows ARM64 | shiguangfrp-windows-arm64.exe |
| Linux 64位 | shiguangfrp-linux-amd64 |
| Linux ARM64 | shiguangfrp-linux-arm64 |
| Android APK | shiguangfrp-android-1.0.0.apk |
| Android Termux(64) | shiguangfrp-android-arm64 |
| Android Termux(32) | shiguangfrp-android-arm |

> 正式安装包在右侧「Releases」中下载；文件名与 SHA256 见各版本发布说明。

## 使用

1. 下载并运行对应平台客户端；
2. 浏览器打开 `http://127.0.0.1:9901/`；
3. 填入面板地址与访问密钥（面板「个人中心」查看），隧道自动同步启动。

一键安装（Linux）：
```bash
curl -fsSL https://frp.acesb.top/dl/install.sh | sudo sh
```

## 校验

每个发布版本附 SHA256SUMS.txt，下载后可用 `sha256sum -c SHA256SUMS.txt` 校验。

历史版本请前往 Releases 页面查找。
