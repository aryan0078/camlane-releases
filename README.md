# Camlane releases

Downloads for **Camlane**, the free app that turns an Android phone into a low-latency webcam and microphone for Windows, macOS and Linux over Wi-Fi or LAN.

**Get Camlane:** https://aryan0078.github.io/camlane/download/

The download page picks the right file for your computer and always points at the newest release. This repository only hosts the release files; the [Releases](https://github.com/aryan0078/camlane-releases/releases) tab lists every version.

| Platform | Files | Status |
|----------|-------|--------|
| Android 8+ | `camlane-android.apk`, or Google Play (coming soon) | stable |
| Windows 10 and 11 | `camlane-desktop-windows-x86_64-setup.exe`, `.msi` | stable; virtual camera is experimental |
| macOS | `camlane-desktop-macos-aarch64.dmg` (Apple silicon), `camlane-desktop-macos-x86_64.dmg` (Intel) | beta: preview and audio work, virtual camera coming soon |
| Linux | `camlane-desktop-linux-x86_64.AppImage`, `.deb` | stable |
| Command line | `camlane-cli-<platform>.tar.gz` / `.zip` | stable |

Each release includes `SHA256SUMS.txt`. To check a download:

```sh
sha256sum -c SHA256SUMS.txt --ignore-missing
```

The Android APK shows one small banner ad per screen to fund development. Ads never cover the camera, and no feature is locked. [Privacy policy](https://aryan0078.github.io/camlane/privacy/).

Camlane is licensed under the Apache License 2.0 (see `LICENSE` and `NOTICE`). The source code repository opens to the public soon.

Report problems by opening an issue in this repository.
