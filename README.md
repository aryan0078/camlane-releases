# Camlane releases

Downloads for **Camlane**, the free app that turns an Android phone into a low-latency webcam and microphone, or a room camera, for Windows, macOS and Linux over Wi-Fi or LAN.

**Get Camlane:** https://camlane.live/download

The download page picks the right file for your device and always points at the newest release. This repository only hosts the release files; the [Releases](https://github.com/aryan0078/camlane-releases/releases) tab lists every version.

| Platform | Files | Status |
|----------|-------|--------|
| Android 8+, phones and tablets | `camlane-android.apk` (Google Play listing after closed testing) | stable |
| Windows 10 and 11 | `camlane-desktop-windows-x86_64-setup.exe` | stable; virtual camera is experimental |
| macOS | `camlane-desktop-macos-aarch64.dmg` (Apple silicon), `camlane-desktop-macos-x86_64.dmg` (Intel) | beta: preview and audio work, virtual camera coming soon; not notarised yet, so right-click the app and choose Open the first time |
| Linux | `camlane-desktop-linux-x86_64.AppImage`, `camlane-desktop-linux-x86_64.deb` | stable |
| Command line | `camlane-cli-<platform>.tar.gz` / `.zip` | stable |

Some releases also include `camlane-desktop-windows-x86_64.msi`. 0.2.0 doesn't, so use the setup installer.

## What you get

- **Your phone as a webcam and microphone.** It shows up as "Camlane Camera" and "Camlane Microphone" in Zoom, Meet, Teams, OBS, Discord and browsers, over Wi-Fi or a phone hotspot, with no internet or account.
- **Pro camera controls:** up to 4K, 1440p or 1080p at 60 fps, manual ISO, shutter, focus and white balance, zoom across lenses, torch and stabilisation, all adjustable from the computer during a call.
- **Auto-framing with zoom lock:** keeps your face in frame and at the same size as you move.
- **Looks:** background blur, filters, colour adjustments and your own 3D LUTs.
- **Low latency:** hardware video encoding. If the computer's firewall blocks the phone, the computer connects to the phone instead.

## New in 0.2

- **Three modes:** Share camera and mic (your computer's webcam and mic), Camera (a room or security camera, with night mode, motion zones and sound events), and Watch on the computer (record and watch your cameras).
- **Recordings on your own computer:** per camera Off, Motion only or Continuous, with sound only where you turn it on; encrypted, kept 1 week by default; playback from 0.25× to 100×, a month heatmap, MP4 export and a Storage page with Free up space. Camera phones record on themselves while no computer answers.
- **Watch from other computers:** live video, battery and heat, the timeline, downloads, and alerts, including motion and noise with a thumbnail.
- **Camera wall:** up to 16 cameras, full screen or in their own windows, with live zoom.
- **Studio sound:** noise cancellation, presets, a steady loudness level, meters and echo cancellation.
- **Several phones at once:** an auto mixer, a stereo pair, a spatial mix, an auto-director, picture-in-picture, side-by-side and grid layouts, ISO recording, color match and cues.
- **Battery saver** for room cameras, standby for cameras nobody watches, and steps down before a phone overheats.
- **Two-way audio:** talk from your computer through a camera phone.
- **Privacy mode:** an instant camera and mic kill switch, from the app, Quick Settings or a voice phrase you choose.
- **Mic on and off per camera,** for streaming and for recordings.
- **Private AI, fully offline** (desktop, off by default): a people library, activities, highlights, day summaries and a natural offline voice. Nothing leaves your computer.

**Coming next:** an iPhone and iPad app (beta), a phone that records with no computer, recordings kept across several of your devices, privacy rules that cut or blur what you choose, and watching your cameras away from home.

**Google Play:** Camlane is in closed testing, and a public listing follows. Until then, use the APK from the Releases tab.

Each release includes `SHA256SUMS.txt`. To check a download:

```sh
sha256sum -c SHA256SUMS.txt --ignore-missing
```

The Android APK shows one small banner ad per screen to fund development. Ads never cover the camera, and no feature is locked. [Privacy policy](https://camlane.live/privacy).

Help: https://camlane.live/help. Report problems by opening an issue in this repository.
