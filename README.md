# HamDMR
The better version of DroidStar for Windows!

# HamDMR 📡

[![Release](https://img.shields.io/github/v/release/TA1EEI/HamDMR?color=00E5FF&label=Release)](https://github.com/TA1EEI/HamDMR/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows%20x64-007ACC?logo=windows)](https://github.com/TA1EEI/HamDMR/releases)
[![License](https://img.shields.io/badge/License-GPLv2-green.svg)](LICENSE)

**HamDMR** is a modern, tactical digital voice client engineered for DMR, YSF, P25, NXDN, and D-Star networks. Built on top of the battle-tested DroidStar engine, HamDMR introduces a native **APRS-IS client**, live telemetry, bidirectional **Maidenhead locator calculations**, and a sleek cyber-dark interface optimized for desktop operation.

> **Crafted with passion for the amateur radio community by TA1EEI.**

---




## 🙏 Credits & Special Attribution

HamDMR is a dedicated fork and enhancement of **DroidStar**, originally created by **Doug McLain (nostar / AD8DP)**.

Heartfelt gratitude and utmost respect to Doug for his relentless work and open-source contributions that have empowered thousands of amateur radio operators worldwide to stay connected across digital voice modes.

---

## ✨ Features

- **Integrated APRS-IS Client:**
  - Real-time packet ingestion stream with automatic callsign highlighting.
  - Periodic automated position beaconing with customizable SSID and comments.
  - Bidirectional text messaging with delivery status tracking.
  - Fast telemetry checkouts via embedded [aprs.fi](https://aprs.fi) radar links.
- **Bidirectional Maidenhead Grid Converter:**
  - Dynamic coordinate translation: Edit your decimal Lat/Lon to calculate your QTH Locator (e.g., `KN41aa`), or type a grid to automatically update your coordinates.
- **Modernized Dark Tactical Theme:**
  - High-contrast, glare-free dark palette designed for late-night shack sessions.
  - Launches automatically in maximized desktop mode (`Window.Maximized`).
- **Privacy First (Zero Credential Leakage):**
  - DMR IDs, callsigns, and BrandMeister security keys are stored exclusively in the host's Windows Registry (`HKCU\Software\nostar\DroidStar`). Distributed binaries are completely portable and leak no private credentials.

---

## 📋 Prerequisites

To access digital voice reflectors and talkgroups:
1. **Valid Amateur Radio Callsign.**
2. **DMR ID:** Issued free of charge at [RadioID.net](https://radioid.net).
3. **BrandMeister Hotspot Security Password:** Configured inside your BrandMeister SelfCare panel (`SelfCare -> Hotspot Security`).
4. **AMBE Vocoder Plugin:** Required for digital voice synthesis and decoding.

---

## 🚀 Quick Start (Windows 64-bit)

### 1. Download Standalone Release
Grab the latest pre-compiled archive from the [Releases](https://github.com/YOUR_GITHUB_USERNAME/HamDMR/releases) page:
- Download `HamDMR-v1.0.0-win64.zip`.
- Extract all contents to an accessible folder (e.g., `C:\HamDMR`).
- Launch `DroidStar.exe` (or `HamDMR.exe`).

### 2. Software Vocoder Installation
Due to licensing requirements, the AMBE vocoder plugin is not distributed within the binary package. Load it via either method below:

* **Method A (In-App Automatic Download - Recommended):**
  1. Go to the **Settings** tab.
  2. Paste this link into the **Vocoder URL** field:
     ```text
     [http://pizzanbeer.net/droidstar/plugins/vocoder_plugin.winnt.x86_64](http://pizzanbeer.net/droidstar/plugins/vocoder_plugin.winnt.x86_64)
     ```
  3. Click the download button in the app.

* **Method B (Manual Download):**
  1. Download the plugin directly from [pizzanbeer.net plugins directory](http://pizzanbeer.net/droidstar/plugins/vocoder_plugin.winnt.x86_64).
  2. Place `vocoder_plugin.winnt.x86_64` directly in the root directory alongside your `.exe` file.
  3. In **Settings**, ensure the **Vocoder** dropdown is set to **Software vocoder**.

### 3. Database Updates & Configuration
1. In the **Settings** tab, fill in your **Callsign**, **DMR ID**, and **BM Pass**.
2. Click **Update hosts** and **Update ID files** to download the latest global talkgroup lists and public amateur radio DMR registries (enables real-time station callsign and name resolution on RX).
3. Switch to the **Main** tab, choose your Talkgroup, and you are on the air!

---

## 📡 APRS-IS Tracking Setup

1. Open the **APRS** tab.
2. Click **APRS EDIT ⚙** and verify your callsign, SSID (e.g., `-7` for handhelds, `-9` for mobile stations), and beacon comment.
3. Update either your coordinates or your 6-character **QTH Locator** (Maidenhead Grid).
4. Click **START TRACKING** to establish the APRS-IS connection.

---

## ⚖️ License

HamDMR is released under the GNU General Public License v2.0 (GPLv2), adhering to the licensing terms of the original DroidStar codebase.

---

**73 de TA1EEI**  
*Good DX & Clear Signals!*

---

## 📸 Screenshots

<img width="1917" height="1034" alt="image" src="https://github.com/user-attachments/assets/34c68226-1a5f-49f3-b6a3-233c9eb3f1a3" />
<img width="1919" height="1032" alt="image" src="https://github.com/user-attachments/assets/5be41922-a064-470d-bf8a-2a120dff6be3" />
<img width="1919" height="1032" alt="image" src="https://github.com/user-attachments/assets/783b8e99-e172-4396-8e6e-d1ee54745e9e" />
<img width="750" height="554" alt="image" src="https://github.com/user-attachments/assets/56db8d51-7310-4234-ae0c-f788d8622264" />



