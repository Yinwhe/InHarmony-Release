# InHarmony Release

This repository is used only for published release assets for In Harmony.

It does not contain application source code.

## Android

Android builds are distributed through GitHub Releases.

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
