# InHarmony Release

This repository is used for published release assets for In Harmony.

It does not contain application source code.

## About In Harmony

In Harmony is a cross-platform LAN rehearsal metronome for musicians playing together on nearby
devices.

One device creates a room, other devices join over the same local network, and the room shares the
same tempo, meter, and transport state so each device can render its own local click in sync.

## Android

Android builds are distributed through GitHub Releases in this repository.

### Requirements

- Android 8.0 or later
- Devices should be on the same local network for room discovery and sync

### First Use

1. Install the APK from the latest release.
2. Grant network and microphone access if Android prompts for them.
3. Keep devices on the same Wi-Fi or local network.

### Basic Usage

1. Open In Harmony on one device and tap `CREATE ROOM`.
2. Open In Harmony on another device and tap a room from `AVAILABLE ROOMS`.
3. Use the host device to control tempo, time signature, and transport.
4. Use each device's local audio settings or route compensation if output timing needs adjustment.

### Release Assets

Recommended asset naming:

- `InHarmony-android-v1.0.0.apk`

Recommended release naming:

- Tag: `android-v1.0.0`
- Title: `In Harmony Android v1.0.0`

## Release Checklist

1. Build the signed release APK from the main application repository.
2. Rename the APK to the final versioned filename.
3. Compute the SHA-256 checksum.
4. Draft a new GitHub Release in this repository.
5. Upload the APK as a release asset.
6. Paste the prepared release notes.
7. Publish as a pre-release first if the build is not broadly validated.
