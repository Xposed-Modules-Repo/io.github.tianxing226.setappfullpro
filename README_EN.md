# SetAppFull pro

[简体中文](README.md) | [English](README_EN.md)

An LSPosed module for **per-app immersive fullscreen**, supporting modern libxposed APIs 101 and 102.

**[Download the latest APK](https://github.com/tianxing226/SetAppFull-pro/releases/latest)** · [Telegram channel](https://t.me/tiaxcj) · [Verification notes](https://github.com/tianxing226/SetAppFull-pro/blob/master/docs/VERIFICATION_EN.md)

## 2.0.3 update

Fixed status bars remaining visible on some physical devices, improved Activity window and hook argument handling, and fixed the extra top strip in Relief Map. Version remains 2.0.3.

## Features

- Per-app immersive fullscreen with separate status bar, navigation bar, and cutout rules.
- Manually enable “Allow screenshots” in app details; off by default and subject to DRM and hardware limits.
- Home screen framework status plus searchable app rules and filters.
- Android 11+ and modern LSPosed / libxposed API 101/102.

## Usage

1. Install the APK and enable **SetAppFull pro** in LSPosed.
2. Add target apps to the module scope.
3. Choose each app in Settings and enable the needed rules.
4. Restart the target app to check the result.

## Verification and limits

Version 2.0.3 was verified on a Xiaomi Android 17/API 37 phone with Relief Map and Douyin; the MuMu regression suite passed 22/22. No separate Android 16 physical device or dedicated PopupWindow scenario was available. DRM and hardware-secure content remain subject to Android and vendor restrictions.

This is an independently maintained fork of [cokkeijigen/SetAppFull](https://github.com/cokkeijigen/SetAppFull), licensed under [AGPL-3.0](LICENSE).
