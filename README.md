# Camlane releases

Downloads for **Camlane**, the free app that turns an Android phone into a low-latency webcam and microphone for Windows, macOS and Linux over Wi-Fi or LAN.

**Get Camlane:** https://aryan0078.github.io/camlane/download/

The download page picks the right file for your computer and always points at the newest release. This repository only hosts the release files; the [Releases](https://github.com/aryan0078/camlane-releases/releases) tab lists every version.

| Platform | Files | Status |
|----------|-------|--------|
| Android 8+, phones and tablets | `camlane-android.apk` (Google Play listing after closed testing) | stable |
| Windows 10 and 11 | `camlane-desktop-windows-x86_64-setup.exe`, `.msi` | stable; virtual camera is experimental |
| macOS | `camlane-desktop-macos-aarch64.dmg` (Apple silicon), `camlane-desktop-macos-x86_64.dmg` (Intel) | beta, build coming shortly: preview and audio work, virtual camera coming soon |
| Linux | `camlane-desktop-linux-x86_64.AppImage`, `.deb` | stable |
| Command line | `camlane-cli-<platform>.tar.gz` / `.zip` | stable |

## What you get

- **Your phone as a webcam and microphone.** It shows up as "Camlane Camera" and "Camlane Microphone" in Zoom, Meet, Teams, OBS, Discord and browsers, over Wi-Fi or a phone hotspot, with no internet or account.
- **Pro camera controls:** up to 4K, 1440p or 1080p at 60 fps, manual ISO, shutter, focus and white balance, zoom across lenses, torch and stabilisation. All of them can be adjusted from the computer during a call.
- **Auto-framing with zoom lock:** keeps your face in frame and at the same size as you move.
- **Looks:** background blur, filters, colour adjustments and your own 3D LUTs.
- **Several phones at once:** a multiview, cuts between angles, and Live/Standby tally lights.
- **Low latency:** hardware video encoding. If the computer's firewall blocks the phone, the computer connects to the phone instead.

**Coming in the next release:** studio sound with noise cancellation, a battery saver for room cameras, an auto-director that cuts to whoever is speaking, and picture-in-picture layouts. **Planned after that:** Watch mode with a camera wall and recordings, privacy mode (an instant camera and mic kill switch), mic on/off per camera, night mode, motion zones and noise alerts, and two-way audio.

**Google Play:** Camlane is in closed testing, and a public listing follows. Until then, use the APK from the Releases tab.

Each release includes `SHA256SUMS.txt`. To check a download:

```sh
sha256sum -c SHA256SUMS.txt --ignore-missing
```

The Android APK shows one small banner ad per screen to fund development. Ads never cover the camera, and no feature is locked. [Privacy policy](https://aryan0078.github.io/camlane/privacy/).

Camlane is licensed under the Apache License 2.0 (see `LICENSE` and `NOTICE`). The source code repository opens to the public soon.

Report problems by opening an issue in this repository.
