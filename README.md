# NEROKIT Studio - Universal After Effects Extension

[![After Effects](https://img.shields.io/badge/Adobe%20After%20Effects-2017%20--%202026+-blue.svg)](https://www.adobe.com/products/aftereffects.html)
[![Version](https://img.shields.io/badge/Version-v1.2.0-emerald.svg)](https://github.com/unoxeo/NEROKIT/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-orange.svg)]()
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)]()

> **NEROKIT** is an all-in-one professional Adobe After Effects workflow suite featuring a real-time Bezier Graph Editor with custom image backgrounds, multi-effect preset stacking, timeline layer management, and automatic keyframe easing.

---

## ⚡ Quick 1-Click Installation (Windows)

1. **Download or Clone** this repository:
   - Click the green **Code** button $\rightarrow$ **Download ZIP**.
   - Extract the ZIP folder to your computer.
2. **Run Installer**:
   - Right-click **`INSTALL_NEROKIT.bat`** (or `INSTALL_NEROVVKIT.bat`) and choose **"Run as administrator"**.
   - The installer automatically enables Adobe Developer Mode (`PlayerDebugMode`) across all After Effects versions and deploys the extension in seconds.
3. **Open After Effects**:
   - Restart Adobe After Effects.
   - Go to: **Window $\rightarrow$ Extensions $\rightarrow$ nerokit** (or run `NEROKIT_Ae.jsx` from **File $\rightarrow$ Scripts $\rightarrow$ Run Script File...**).

---

## 🚀 Key Features

- **Titanium Bezier Graph Editor**:
  - Drag control handles with live visual feedback.
  - Custom image background support (JPG, PNG, WebP) with adjustable opacity & blur.
  - Auto Apply Graph: Instantly eases selected timeline keyframes on handle drag or release.
  - Copy Easing Curve directly from timeline keyframes.
- **Multi-Effect Cumulative Preset Stacking**:
  - Apply unlimited `.ffx` presets (Shake, Halftone, Glow, Tritone) onto the same layer without overwriting existing effects.
- **Customizable Themes & UI Scaling**:
  - 7 handcrafted color schemes (Dark Emerald, Ocean, Violet, Amber, Crimson, Slate, Custom).
  - Live HSL + Alpha color sliders.
  - 95%, 100%, and 105% UI scaling.
- **In-App Auto Update Checker**:
  - Open **Settings** $\rightarrow$ Click **Check for Updates** to instantly verify and download the newest releases directly from GitHub.

---

## 🛠️ Troubleshooting

- **Extension doesn't appear under `Window -> Extensions`?**
  - Run `INSTALL_NEROKIT.bat` as Administrator. Adobe requires `PlayerDebugMode = 1` in Windows Registry, which the installer sets automatically.
- **Using a portable or restricted After Effects version?**
  - Use the included standalone script: In AE, go to **File $\rightarrow$ Scripts $\rightarrow$ Run Script File...** and select **`NEROKIT_Ae.jsx`**. It launches the full UI without needing CEP!

---

## 🔄 Updates

To update, download the latest release files and re-run `INSTALL_NEROKIT.bat`. All your custom curves, presets, and background images are permanently saved on disk in `%APPDATA%\NEROKIT\nerokit_preferences.json` and will never be deleted.

---
© 2026 NEROKIT Studio. All rights reserved.
