# 卖家岛 · Windows 发行

这里仅保存卖家岛的 Windows 安装包、更新签名及发行说明，不包含源码、店铺配置或任何凭据。

## 下载

进入 [banben/windows](banben/windows/) 下载 Windows x64 安装包，或进入 [banben/macos](banben/macos/) 下载 macOS (Apple Silicon) 版本并阅读对应说明。

## 应用内更新

从 **0.5.0** 开始，可在卖家岛的 **设置 → 关于 → 检查更新** 检查新版本。程序校验版本绑定签名，下载完成后需要再次确认安装。

0.4.7 及更早的 Windows 版本需要手动安装一次 0.5.0。升级时选择原安装目录，勿先卸载，保留本机配置。

本仓库不保存更新签名私钥。Windows Authenticode、Apple 公证与应用内更新签名不是一回事：Windows 安装时可能显示未知发布者提醒，macOS 首次打开需右键 → 打开。

## 升级顺序

- 上传新安装包/签名并验证可下载后，才更新对应平台的 `latest.json`。
- Windows 与 macOS 使用同一个更新签名身份，但版本清单相互独立。
