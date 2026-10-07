# 伴岛 Android

伴岛是一款结合角色陪伴、番茄专注与轻养成的 Android 应用，支持蓝毛小女仆与知墨 · Codex 娘。使用 AI 编程与图像生成工具辅助开发和素材制作。

## 当前版本：0.16.3

- **专注**：设定小目标，明确点击后开始计时，支持暂停、继续和独立休息；双击场景进入横屏小屋。
- **桌面**：悬浮角色陪伴、摸头、猜拳、自定义手势和安静模式，按需要控制主动打扰。
- **羁绊**：完成专注与日常互动推进五阶段成长，逐步解锁两处场景、四段故事和两组动作；离线不扣进度，奖励可实际使用。
- **同桌小屋**：昼夜与专注/放松四态静态插画，配合实时桌钟显示计时状态，支持光线、场景及雨声设置。

个人项目：需求拆解、交互与成长规则设计、AI 辅助开发、素材接入和结果检查。已有构建、规则回归及模拟器验证；本版尚无真实手机、长期耗电及真实用户体验验收。详细更新与验证范围见 [0.16.3 发布说明](https://github.com/BreakYukino/bandao-android-releases/releases/tag/v0.16.3)。

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
