# SetAppFull pro

按应用设置 **沉浸式全屏 / immersive fullscreen**，分别控制状态栏、导航栏和屏幕挖孔区域。支持现代 LSPosed / libxposed **API 101、102**。

**[下载 APK](https://github.com/tianxing226/SetAppFull-pro/releases/latest)** · [源码](https://github.com/tianxing226/SetAppFull-pro) · [Telegram 频道](https://t.me/tiaxcj)

## 功能

- 为每个应用单独开启或关闭全屏规则。
- 分别隐藏状态栏、导航栏，允许内容延伸至显示缺口区域。
- 主页显示框架连接状态、版本和 API，设置页支持搜索与筛选应用。
- 液态玻璃“主页 / 设置”导航，支持深浅色主题。

全屏效果取决于应用和系统，不能保证去除应用自身的黑边，也不会强制拉伸画面。多窗口、画中画和浮动窗口会暂停策略，键盘出现时会释放导航栏控制。

## 安装使用

需要 **Android 11 或更新版本**，以及正常工作的现代 libxposed 兼容框架（API 101 或 102）。仅安装 APK 不会自动使其他应用全屏。

1. 安装 APK，在框架管理器中启用 **SetAppFull pro**。
2. 打开主页确认框架状态，再到“设置”找到目标应用。
3. 授予目标应用作用域，开启全屏并设置系统栏、缺口规则。
4. 重新启动目标应用，检查效果；关闭规则后重新启动可恢复默认显示。

标准 Android 的应用列表权限在安装时授予，部分厂商系统另有授权要求。列表不完整时可从设置页进入系统权限设置。

**独立包名：`io.github.tianxing226.setappfullpro`。** 从旧版 `ss.colytitse.setappfull` 切换时，新旧应用可以共存，但配置和作用域不会自动迁移。请重新启用新模块、设置规则，并关闭旧模块对相同应用的作用域。

## 手机界面

以下是 **2.0.1** 在 Android 17 **手机模拟器**中的真实截图，用于展示界面，不代表 2.0.2 新包名版本的测试结果。Probe 是项目测试应用。

<table>
  <tr>
    <td align="center">主页与框架状态</td>
    <td align="center">应用列表</td>
    <td align="center">全屏规则</td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/tianxing226/SetAppFull-pro/65d99e9a14ce1812d39c27b7fc5049dfe60e2c73/docs/screenshots/home.png" width="230" alt="SetAppFull pro 主页与框架状态"></td>
    <td><img src="https://raw.githubusercontent.com/tianxing226/SetAppFull-pro/65d99e9a14ce1812d39c27b7fc5049dfe60e2c73/docs/screenshots/apps.png" width="230" alt="应用列表与筛选"></td>
    <td><img src="https://raw.githubusercontent.com/tianxing226/SetAppFull-pro/65d99e9a14ce1812d39c27b7fc5049dfe60e2c73/docs/screenshots/rules.png" width="230" alt="每个应用的系统栏和显示缺口规则"></td>
  </tr>
</table>

## 验证与来源

验证范围与已知限制见 [验证说明](https://github.com/tianxing226/SetAppFull-pro/blob/master/docs/VERIFICATION.md)，本次包名变更说明见 [2.0.2 更新说明](https://github.com/tianxing226/SetAppFull-pro/blob/master/RELEASE-2.0.2.md)。厂商 ROM、ARM 真机、实体挖孔屏和小米真实权限弹窗仍需对应设备验证。

本项目是 [cokkeijigen/SetAppFull](https://github.com/cokkeijigen/SetAppFull) 的独立维护分支，不是原作者发布的版本。保留原作者归属与 [AGPL-3.0](https://github.com/tianxing226/SetAppFull-pro/blob/master/LICENSE) 许可证。液态玻璃来自 [Kyant0/AndroidLiquidGlass](https://github.com/Kyant0/AndroidLiquidGlass) / Backdrop，其他依赖见 [第三方声明](https://github.com/tianxing226/SetAppFull-pro/blob/master/THIRD_PARTY_NOTICES.md)。
