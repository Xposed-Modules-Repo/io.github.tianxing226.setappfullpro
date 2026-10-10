# SetAppFull pro

[简体中文](README.md) | [English](README_EN.md)

An Android module for per-app immersive fullscreen control of system bars and display cutouts. Supports modern LSPosed / libxposed API 101 and 102.

**[Download the latest release APK](https://github.com/tianxing226/SetAppFull-pro/releases/latest)** · [Telegram channel](https://t.me/tiaxcj) · [Public compatibility notes](https://github.com/tianxing226/SetAppFull-pro/blob/master/docs/VERIFICATION_EN.md)

This repository is the module-repository mirror. See the [main repository](https://github.com/tianxing226/SetAppFull-pro) for current source and public compatibility notes.

## 2.0.6

- Confirming a framework scope supplies defaults for an app with no explicit rule.
- Enabling fullscreen in the app requests scope authorization and distinguishes pending authorization, synchronized rules, and restart-required states.
- Home and Settings use solid surfaces and include a concise tutorial.
- A version-gated Bilibili Story portrait-player adjustment removes reserved space without forced stretching and can be disabled per app.

## Usage

1. Install the APK and enable **SetAppFull pro** in the framework manager.
2. Select the target app in framework scope, or enable it in the app and follow the authorization prompt.
3. Restart the target app when prompted and verify the result. Existing custom rules, explicit disables and resets take precedence.

Scope authorization remains controlled by the framework. Native aspect-ratio borders, encoded video borders, DRM and hardware protection may remain.

## License

Based on [cokkeijigen/SetAppFull](https://github.com/cokkeijigen/SetAppFull) under [AGPL-3.0](LICENSE).