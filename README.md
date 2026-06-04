# SideStack

A native Android app store for sideloaded apps built by DamienSmith428. Browse, download, and install apps directly from your device — no Play Store, no accounts, no nonsense.

![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Version](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2FDamienSmith428%2FSideStack-app-public%2Fmain%2Fdocs%2Fconfig.json&query=%24.app.latestVersion&style=flat-square&color=blueviolet&label=Latest+Version)
![Built With](https://img.shields.io/badge/Built%20with-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

---

## What It Does

SideStack is a native Android frontend for the SideStack app store. It pulls app listings directly from each app's config, displays them as clean cards, and lets you browse, read about, and download any app — all without leaving the app or opening a browser.

No account. No subscription. No algorithm. Just your apps, the way you want them.

---

## Features

### App Store
- Browse all available apps from a single native interface
- App cards show icon, name, tagline, category, and current version
- Pull to refresh to check for newly added apps

### In-App Downloads
- Tap any app card to view its full page inside the app
- Download APKs directly within the app — no browser required
- Install prompt triggers automatically when the download completes

### Search
- Filter apps by name, category, or description instantly
- Results update as you type

---

## Installation

SideStack is not on the Google Play Store. You install it by sideloading the APK.

**1. Download the APK**

Head to the [latest release](https://github.com/DamienSmith428/SideStack-app-public/releases/latest) and download the APK.

**2. Enable unknown sources on your device**

- Android 8 and above: **Settings → Apps → Special App Access → Install Unknown Apps** → select your browser or file manager and enable it

**3. Open the APK and tap Install**

No account, no setup, no permissions you did not agree to.

---

## Releases

A single universal APK is provided for each release.

| File | Description |
|---|---|
| `app-vX.X-release.apk` | Universal build — works on all supported devices |

---

## Permissions

SideStack requests only the permissions it actually needs:

| Permission | Reason |
|---|---|
| Internet | Loading app listings and downloading APKs |
| Request Install Packages | Triggering the install prompt after a download completes |

No contacts, no location, no microphone, no camera.

---

## Privacy

SideStack does not collect, transmit, or store any personal data. Everything stays on your device. The only network activity is loading app configs and downloading APKs you explicitly choose to download.

---

## App Store

The full SideStack web store is available at **[damiensmith428.github.io/SideStack-web](https://damiensmith428.github.io/SideStack-web/)** — browse all available apps and download directly from your browser if you prefer.

---

## Contributing

This is a personal project. If you find a bug or have a feature idea, open an issue and I will take a look when I can.

---

## Source Code

Source code is maintained in a private repository.
