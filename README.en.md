<p align="center"><img src="img/ikon.png" width="96" alt="BASTION Disk"></p>

<h1 align="center">BASTION Disk</h1>
<p align="center"><b>See your disk filling up before it's full.</b><br>A tactical disk panel that docks on any edge of your Mac's screen.</p>

<p align="center"><a href="README.md">Türkçe</a> · <b>English</b></p>

<p align="center">
  <a href="https://github.com/dagcann34/BASTION-Disk/releases/latest"><b>⬇️ Free download (macOS 14+, Apple Silicon)</b></a>
  &nbsp;·&nbsp; 🔑 Pro license: <a href="https://dagcannural.com">dagcannural.com</a> · Instagram <a href="https://instagram.com/instahaber.io">@instahaber.io</a>
</p>

<p align="center"><img src="img/kapak.png" width="420" alt="BASTION Disk cover"></p>

> **Language note:** The app's interface is currently in **Turkish only**. Menu and button names below are given in Turkish as they appear in the app, with an English translation in parentheses.

## What it does

- **SEE** — Free space, a segmented usage gauge and a live counter in the menu bar.
- **FIND** — A TreeSize-style browser: folders sorted by size, hidden folders included (`~/Library`, `.cache`, package caches).
- **CLEAN** — Move to Trash (undoable), or delete permanently with Pro. Core macOS folders are protected, sensitive locations get an extra warning, and every permanent action asks for confirmation.
- **FOUR EDGES, ONE PANEL** — The panel sits on the bottom, top, left or right edge; other windows (maximized ones included) snap up to its edge.
- **39 THEMES, 7 FAMILIES** — Pick your own fonts and backdrop, or use your own image.
- **NO NETWORK, NO TELEMETRY** — The app never connects to any server. Even the license is verified offline, on this Mac.

<p align="center"><img src="img/dort-kenar.png" width="380" alt="Four edges"> <img src="img/temalar.png" width="380" alt="Themes"></p>

## Free and Pro

| | Free | Pro — lifetime **1,000 TRY** |
|---|---|---|
| Free-space gauge, browser | ✓ | ✓ |
| Move to Trash, empty Trash | ✓ | ✓ |
| 4 edges + window snapping | ✓ | ✓ |
| Themes | 4 | 39 |
| Permanent delete, empty folder, admin delete | — | ✓ |
| Xcode simulator cleanup | — | ✓ |
| Fonts, all backdrops, your own image | — | ✓ |
| 1.x updates | ✓ | ✓ |

The version you download is the **free version**. Pro features unlock in the same app with a license key, so there is nothing to re-download.

## Installation

1. From the [Releases](https://github.com/dagcann34/BASTION-Disk/releases/latest) page, download **`BASTION.Disk.1.4.0.dmg`** (drag and drop) or **`BASTION.Disk.1.4.0.pkg`** (installer wizard).
2. DMG: open it and drag **BASTION Disk** into the **Applications** folder. PKG: open it and follow the steps.
3. **First launch (macOS 15 and later):** The app has not been through Apple notarization yet, so macOS blocks it the first time.
   - Click **Done** on the warning.
   - Go to **System Settings › Privacy & Security** and, at the bottom, next to *"BASTION Disk was blocked"*, click **Open Anyway**.
   - Enter your password / Touch ID, then choose **Open Anyway** again in the dialog. This is needed only once.
   - On macOS 14, right-clicking the app in Finder › **Open** also works.
4. **Permissions (once):** System Settings › Privacy & Security:
   - **Accessibility** → turn on BASTION Disk (for window snapping).
   - **Full Disk Access** → turn on BASTION Disk (so you are not asked folder by folder).

## Activating your Pro license

1. Copy the **whole** key you received by email after purchase; it starts with **`BSTN1.`**
2. Click **"PRO · 1.000 TL"** on the panel (or go to **Ayarlar › Genel › Lisans › Lisans gir** — *Settings › General › License › Enter license*).
3. Paste the key into the **Lisans anahtarı** (*License key*) box and click **Etkinleştir** (*Activate*). A **PRO** badge appears next to the logo.

Verification happens on this Mac. No internet is needed and no information is sent.

## Verifying integrity

You can check in Terminal that the downloaded files are unchanged (download `SHA256SUMS` into the same folder as the two installer files):

```
shasum -a 256 -c SHA256SUMS
```

```
e716eb7e8c2d5df9d24a3e5eee63b59d3a2080f4314be5815b62aeaf68b2deb2  BASTION.Disk.1.4.0.dmg
91830bf1c9ec45f251aaf806338ecdcfd08d8ec02655d3327f6b0ff290a5c414  BASTION.Disk.1.4.0.pkg
```

## Security notes

- No network access, no telemetry. Hardened Runtime is on; the only extra entitlement is sending Finder a command to empty the Trash (Apple Events).
- The core macOS folders themselves and the system volume cannot be deleted; every permanent action asks for a separate confirmation; admin deletion is done only through macOS's own password dialog.
- Known limitation: there is no Apple Developer ID signature or notarization yet (which is why "Open Anyway" is needed on first launch).

## Uninstalling

Run **`BASTION.Disk.i.Kaldir.command`** from Releases: it moves the app to the Trash and removes its login item and settings.

---

© 2026 Dağcan Nural · BASTION. All rights reserved. This repository hosts only installer files and documentation; the source code is not published. The free version may be used for personal and commercial purposes; Pro features may be used only with a purchased license key. The software is provided "as is".
