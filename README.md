# xTTier — eXtended Technical Training for Infrastructure, Engineering & Reliability

<p align="center">
  <b>Languages:</b> <b>English</b> | <a href="README.es.md"><b>Español</b></a>
</p>

<p align="center">
  <a href="https://github.com/netssv/xttier-releases/releases/latest"><img src="https://img.shields.io/github/v/release/netssv/xttier-releases?style=flat-square&color=7c6bb0&label=Latest%20Release" alt="Latest Release"></a>
  <a href="https://xttier.rop-martel.workers.dev"><img src="https://img.shields.io/badge/Tracks-Tier%201%20%7C%20Tier%202%20%7C%20Tier%203%20%7C%20SysAdmin%20%7C%20DevOps-7c6bb0?style=flat-square" alt="Tracks"></a>
  <a href="https://xttier.rop-martel.workers.dev"><img src="https://img.shields.io/badge/Stack-Linux%20CLI%20%7C%20Apache%20%7C%20PHP--FPM%20%7C%20MariaDB%20%7C%20DNS%20%7C%20Exim-5fa882?style=flat-square" alt="Stack"></a>
  <a href="https://xttier.rop-martel.workers.dev"><img src="https://img.shields.io/badge/Simulation-40%2B%20Real--World%20Incidents-181622?style=flat-square" alt="Simulation"></a>
  <a href="https://xttier.rop-martel.workers.dev"><img src="https://img.shields.io/badge/Platforms-Android%20%7C%20iOS%20%7C%20Web%20PWA-5fa882?style=flat-square" alt="Platforms"></a>
  <a href="https://xttier.rop-martel.workers.dev"><img src="https://img.shields.io/badge/PWA-100%25%20Offline%20Capable-524973?style=flat-square" alt="Offline PWA"></a>
</p>

> **xTTier** (*eXtended Technical Training for Infrastructure, Engineering & Reliability* / *eXtended Troubleshooting & Triage for Incident Escalation & Resolution*) is a cross-platform technical training and simulation suite designed to master real-world Linux terminal diagnostics and troubleshooting without endangering live production systems.
> 
> Guided by **`xBooty`**, learners and engineers advance through 5 structured engineering tracks: from frontline support (Tier 1), server administration (Tier 2), and deep incident triage (Tier 3), to enterprise Linux systems administration (SysAdmin) and cloud reliability engineering (DevOps / SRE).

---

## Specialization Tracks & Career Matrix

```
┌───────────────────────────────────────────────────────────────────────────┐
│                        xTTier TRAINING CURRICULUM                         │
├──────────────┬──────────────┬──────────────┬──────────────┬───────────────┤
│    TIER 1    │    TIER 2    │    TIER 3    │   SYSADMIN   │    DEVOPS     │
│   Frontline  │ Server Admin │ Deep Triage  │  Linux Core  │  Cloud & SRE  │
├──────────────┼──────────────┼──────────────┼──────────────┼───────────────┤
│ • DNS & MX   │ • SSH & nano │ • Kernel log │ • cPanel/WHM │ • CI/CD & Git │
│ • HTTP 4xx   │ • Apache/Nginx│ • MySQL dump │ • iptables   │ • 12-Factor   │
│ • Mail ports │ • PHP-FPM    │ • Memory OOM │ • Exim MTA   │ • Containers  │
│ • WHOIS check│ • .htaccess  │ • Disk inode │ • SSL / TLS  │ • Reliability │
└──────────────┴──────────────┴──────────────┴──────────────┴───────────────┘
```

---

## Official Direct Installer Downloads

All installer binaries are compiled automatically via verified GitHub Actions CI/CD pipelines and hosted on GitHub's global CDN:

| Platform | Package | Recommended Installation Method | Direct Download |
| :--- | :--- | :--- | :--- |
| **Android** | `xTTier.apk` | Sideload (Enable "Install from Unknown Sources") | [Download APK](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.apk) |
| **iOS / iPad** | `xTTier.ipa` | TrollStore (Permanent / No Revokes) or Sideloadly / AltStore | [Download IPA](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.ipa) |
| **Web PWA** | Web App | Safari / Chrome > *Share > Add to Home Screen* | [Open Web App](https://xttier.rop-martel.workers.dev) |

---

## Step-by-Step Installation Guide

### Android (Direct Sideloading)
1. Download [`xTTier.apk`](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.apk) directly to your Android device.
2. Open the downloaded file from your browser or file manager.
3. If prompted, toggle **Allow from this source** in your Android security settings.
4. Tap **Install** and launch xTTier.

### Apple iOS and iPadOS

#### Option A: TrollStore (Recommended for iOS 14.0 – 17.0)
* Permanent installation with no 7-day re-signing limits and no computer required.
1. Download [`xTTier.ipa`](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.ipa) on your iOS device.
2. Open the file in TrollStore and tap **Install**.
3. xTTier will appear permanently on your home screen.

#### Option B: Sideloadly / AltStore (Any iOS version)
1. Download [`xTTier.ipa`](https://github.com/netssv/xttier-releases/releases/latest/download/xTTier.ipa) to your Mac or PC.
2. Connect your iPhone/iPad via USB or Wi-Fi.
3. Drag `xTTier.ipa` into Sideloadly or AltServer and enter your Apple ID.
4. On your device, navigate to **Settings > General > VPN & Device Management** and trust your Apple ID profile.

#### Option C: Instant PWA Standalone (No Computer, No IPA Required)
1. Open [xttier.rop-martel.workers.dev](https://xttier.rop-martel.workers.dev) in Safari.
2. Tap the **Share** button (`[+]`).
3. Select **Add to Home Screen**.
4. The full offline-capable app will launch in standalone borderless mode.

---

## Automatic In-App Updates

* **Web / PWA:** When a new version is deployed to Cloudflare Pages, a floating banner appears. Clicking **Update** refreshes the Service Worker cache immediately.
* **Native Apps (Android & iOS):** The built-in `VersionUpdater` compares the installed version against production. When a new build is detected, the banner offers a direct **Download** button that opens the system browser to fetch and install the latest package.
* **In-App Changelog:** Click the **`v2.1`** version badge in the titlebar or type `version` / `changelog` in the terminal to view the detailed release notes.

---

## Security, Privacy & Integrity Verification

To verify that your downloaded binary has not been altered, verify the SHA-256 checksum:

```bash
# Verify Android APK
sha256sum xTTier.apk

# Verify iOS IPA
sha256sum xTTier.ipa
```

Compare the output hash against the SHA-256 digest published in the [Latest GitHub Release](https://github.com/netssv/xttier-releases/releases/latest).

> **Privacy Notice:** This distribution repository contains exclusively compiled binaries and documentation. The core source code, proprietary quiz questions, and database schemas are maintained in private development repositories.
