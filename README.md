# SetAppFull pro

[简体中文](README.md) | [English](README_EN.md)

按应用设置**沉浸式全屏**的 LSPosed 模块，支持现代 libxposed API 101/102。

**[下载正式版 APK](https://github.com/tianxing226/SetAppFull-pro/releases/latest)** · [Telegram 频道](https://t.me/tiaxcj) · [验证说明](https://github.com/tianxing226/SetAppFull-pro/blob/master/docs/VERIFICATION.md)

## 2.0.3 更新

修复部分真机状态栏无法隐藏的问题，改善 Activity 窗口和 Hook 参数处理，并修复 Relief Map 顶部白边。版本号保持 2.0.3。

## 功能

- 按应用开启沉浸式全屏，分别控制状态栏、导航栏和挖孔区域。
- 应用详情中手动开启“允许截屏”，默认关闭；DRM 和硬件保护不保证。
- 主页显示 LSPosed 状态，设置页支持应用搜索、筛选和规则管理。
- 支持 Android 11+、现代 LSPosed / libxposed API 101/102。

## 使用

1. 安装 APK，在 LSPosed 中启用 **SetAppFull pro**。
2. 将目标应用加入模块作用域。
3. 在设置中选择目标应用并开启需要的规则。
4. 重启目标应用检查效果。

## 验证与限制

2.0.3 已在小米 Android 17/API 37 真机验证 Relief Map 和抖音的状态栏隐藏；MuMu 回归测试 22/22 通过。Android 16 独立实体设备和 PopupWindow 专用场景未单独验证，DRM 或硬件安全内容仍受系统限制。

本项目是 [cokkeijigen/SetAppFull](https://github.com/cokkeijigen/SetAppFull) 的独立维护分支，采用 [AGPL-3.0](LICENSE) 许可证。
