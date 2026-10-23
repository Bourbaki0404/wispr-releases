# Wispr Android releases

Public update feed for the native Wispr Android app (`app.wispr.messenger.native`).
Application source is maintained in a separate private repository.

- Update origin: https://wispr-update.pages.dev/update.json
- Direct manifest: https://github.com/Bourbaki0404/wispr-releases/releases/latest/download/update.json
- Each non-prerelease Release contains a versioned APK and `update.json`.
- The manifest records the package ID, version, APK URL, byte size and SHA-256.
- The app verifies the size, digest, package identity and signing certificate before opening Android's installer.

Install each build over the existing app. Do not uninstall unless local identity and conversations should be discarded.
