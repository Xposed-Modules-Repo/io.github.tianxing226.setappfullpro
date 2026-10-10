# SetAppFull pro

[简体中文](README.md) | [English](README_EN.md)

按应用设置**沉浸式全屏**的 Android 模块，独立控制状态栏、导航栏和挖孔区域。支持现代 LSPosed / libxposed API 101、102。

**[下载正式版 APK](https://github.com/tianxing226/SetAppFull-pro/releases/latest)** · [Telegram 频道](https://t.me/tiaxcj) · [主仓库兼容说明](https://github.com/tianxing226/SetAppFull-pro/blob/master/docs/VERIFICATION.md)

本仓库是面向模块仓库的发行镜像；完整源码、最新功能说明和公开兼容说明请见[主仓库](https://github.com/tianxing226/SetAppFull-pro)。

## 2.0.6 更新

- 直接确认框架作用域即可为未配置应用准备默认沉浸式规则。
- 在应用内开启全屏会自动申请作用域，并区分等待授权、规则同步和需要重启等状态。
- 主页和设置页使用纯色设计，并提供简短使用教程。
- 针对已知 Bilibili Story 竖屏播放页面修正播放器内部预留空间，可独立关闭且不强制拉伸视频。

## 使用

1. 安装 APK 并在框架管理器启用 **SetAppFull pro**。
2. 在框架作用域中勾选目标应用，或在应用内开启目标应用并按提示完成框架授权。
3. 按提示重启目标应用并检查效果；已有自定义规则、明确关闭和重置结果优先。

作用域授权仍由框架管理器确认，模块不能绕过授权。视频自身比例留边、内嵌黑边、DRM 和硬件保护可能保留。

## 许可

本项目基于 [cokkeijigen/SetAppFull](https://github.com/cokkeijigen/SetAppFull)，采用 [AGPL-3.0](LICENSE)。