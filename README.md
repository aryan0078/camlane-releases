# Camlane

Cameras for your home, on your own devices. Camlane watches and keeps video from IP cameras and other cameras, finds people, sounds and activity, and tells you. No cloud, no account, no subscription.

**Get Camlane:** https://camlane.live/download

This repository holds the download files. The [Releases](https://github.com/aryan0078/camlane-releases/releases) tab lists every version, and each release includes `SHA256SUMS.txt`.

## How it works

- **Cameras:** IP cameras and other cameras come first. A phone or tablet can also be a camera.
- **Home base:** the device that keeps your video. It can be a computer or a phone, so a home with no computer works.
- **Watching:** Linux, Windows and macOS computers, Android phones and tablets, iPhone and iPad, and TV.
- **Away from home:** one switch, **Watch from anywhere**, lets you watch and control cameras through a relay that cannot read your video. Changing settings stays at home.

## Downloads

| Platform | Files | State |
|----------|-------|-------|
| Android 8+, phones and tablets | `camlane-android.apk` | Available. Google Play is in testing; use the APK until the listing is public |
| Windows 10 and 11 | `camlane-desktop-windows-x86_64-setup.exe` | Available. The virtual camera is experimental |
| macOS | `camlane-desktop-macos-aarch64.dmg` (Apple silicon), `camlane-desktop-macos-x86_64.dmg` (Intel) | Beta. Preview and audio work, the virtual camera is not ready. Not notarised yet, so right-click the app and choose Open the first time |
| Linux | `camlane-desktop-linux-x86_64.AppImage`, `camlane-desktop-linux-x86_64.deb` | Available |
| Command line | `camlane-cli-<platform>.tar.gz` / `.zip` | Available |
| Android TV and Google TV | The Android app | Included in the Android app (watch mode, with the remote). Not yet checked on a real TV |
| iPhone and iPad | Not in the downloads | Beta for testers only. An App Store release comes later |

To check a download:

```sh
sha256sum -c SHA256SUMS.txt --ignore-missing
```

The Android APK shows one small banner ad per screen to fund development. Ads never cover the camera, and no feature is locked. [Privacy policy](https://camlane.live/privacy).

## Available now (0.3.15)

**Cameras**
- Add an IP camera found on your Wi-Fi: sign in, name it, pick a room. Camlane checks what the camera really supports and shows only those controls: turn and zoom, picture settings, night mode, restart, and camera events such as motion, sound, a dark or blurry picture and lost signal.
- A phone or tablet as a camera. It reconnects after Wi-Fi drops and restarts, has a battery saver, night mode and motion areas, and two-way audio.
- A camera wall for up to 16 cameras, with live zoom.
- A phone as a webcam and microphone for your computer ("Camlane Camera" and "Camlane Microphone" in Zoom, Meet, Teams, OBS and Discord), up to 4K, with manual controls, looks, background blur and studio sound.
- Privacy mode: an instant camera and microphone switch.

**Video kept at home**
- Recording per camera: Off, Motion only or Continuous. Encrypted, kept for as long as you choose.
- Playback from 0.25x to 100x, a heatmap of the month, MP4 export, and a Storage page with Free up space.
- Cameras with their own memory card are played from the camera, so nothing is saved twice.
- Older video is kept smaller.

**Smart features** (off until you turn them on, and they run only on your own devices)
- A people library, activities, highlights, day summaries, search of recordings in plain words, and Ask about your home.
- Privacy rules: choose activities that are never recorded, for everyone or for chosen people.
- Alerts for motion, sound and people, and links to other apps.
- Cameras that adjust themselves within limits: brightness and night, following someone, keeping an important moment. Every change is listed, with Undo.

**Devices and homes**
- Add a device with a 6-digit code. Your devices share recordings and settings.
- Watch from anywhere, end to end encrypted, with no account. Join a home from anywhere with a QR code.
- A phone can look after the home, so a home needs no computer.

## Coming in 1.0

The next release is 1.0, on every platform. These parts are already built and waiting for it:

- A new look and simpler screens on computers and Android, and the first iPhone and iPad screens.
- "What happened" that writes itself by minute, hour or day.
- A chat to ask about your home, including long questions.
- Rename people, say two people are the same, and forget a person from any device of your home.
- Alert rules written as sentences, quiet hours that still let urgent alerts through, and privacy rules that can black a camera out.
- Set up the home base, move a camera's video to another device, and see and change storage from another device.
- Camlane can open when your computer starts.
- More for IP cameras: mirror, a night picture for cameras without night mode, motion detection for cameras that have none, and H.265 cameras without extra software.

**Planned, not built yet:** admins (devices that handle permissions for the whole home), the AI driving a camera (turn, zoom, listen), learning each room, fetching a missing clip from the device that has it, letting the AI run everything with a home score, sound and speech understanding, one home base chosen by score, two homes on one device, every feature for IP cameras, and finding lost things.

## Platforms in 1.0

- **Computers and Android:** the new screens are being finished.
- **iPhone and iPad:** started. App Store builds need an Apple developer account first.
- **TV:** the Android app on Android TV and Google TV; a check on a real TV is still to do.
- **Homes with only phones:** every feature is meant to work with no computer.

## Help

https://camlane.live/help. Report problems by opening an issue in this repository.
