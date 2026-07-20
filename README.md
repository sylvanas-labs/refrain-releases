# Refrain — Releases

This public repository hosts release artifacts for **Refrain**, a privacy-first household finance companion for Windows and Android.

> Product source: private. This repository contains public downloads and installation documentation only.

## Downloads

Use the [`alpha-latest`](../../releases/tag/alpha-latest) release for the newest test build.

| Platform | File | Notes |
|---|---|---|
| Android | `Ledger-Scout-Android-*.apk` | Sideload on Android |
| Windows | `Ledger-Scout-Setup-*.exe` | Windows installer |

Alpha builds may contain incomplete features. Do not treat them as stable releases.

## Install on Android

1. Open the `alpha-latest` release on the Android device.
2. Download the `.apk` file.
3. If prompted, allow **Install unknown apps** for the browser or file manager.
4. Open the download and tap **Install**.

Android verifies upgrades using the app's signing identity. Install future releases from this repository so that identity remains consistent.

## Install on Windows

Download the `.exe` file from `alpha-latest`, run it, and follow the installer prompts.

## Release channels

| Channel | Tag | Purpose |
|---|---|---|
| Alpha | `vX.Y.Z-alpha.N` | Versioned test build |
| Latest alpha | `alpha-latest` | Rolling mirror of the newest alpha |

## Rollback

Versioned releases remain available under [Releases](../../releases). On Windows, reinstall an older version. Android generally prevents installing an older version over a newer one; uninstall first only if you accept removing that device's local application data.

