# 伴岛 Android

伴岛是一款安卓桌宠陪伴应用，支持蓝毛小女仆与知墨 · Codex 娘。提供桌面互动、角色成长、纪念物、相处故事，以及外观、动作、台词和手势设置。Codex 使用浅灰日光工作室主题，小女仆保留原有海边小屋风格。

本仓库提供 Android 安装包、更新说明和应用内更新清单。最低支持 Android 8.0。

## 安装与更新

首次使用：进入 [最新版本](https://github.com/BreakYukino/bandao-android-releases/releases/latest)，在附件中下载 `bandao-版本号-debug.apk` 并安装。

已有版本：0.11 起打开「设置 → 应用更新」；0.10 及更早版本打开「伙伴 → 应用更新」。填写以下地址，点「检查更新」：

```text
https://github.com/BreakYukino/bandao-android-releases/releases/latest/download/update.json
```

手机需要能访问 GitHub 及其安装包下载域名；可以使用 Wi-Fi 或移动网络。首次从伴岛安装更新需允许该安装来源，随后在系统安装器确认。覆盖更新保留已有设置，安装后重新打开伴岛，按需召唤桌宠。

目前为个人测试版本，沿用同一调试签名。更新时校验文件大小、SHA-256、包名、版本和签名；系统安装器继续验证安装包。每个版本提供 SHA256SUMS.txt。

## 第三方内容

角色动画来自 [dsh-pet](https://github.com/PC2005-cloud/dsh-pet)，部分互动功能参考 [dsh-pet-indesktop](https://github.com/MerZlin/dsh-pet-indesktop)。授权声明见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)，发布附件也包含完整声明。
