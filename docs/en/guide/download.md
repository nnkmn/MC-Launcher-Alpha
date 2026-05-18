---
title: "Download & Install"
---

# Download & Install

## Download

Go to [GitHub Releases](https://github.com/nnkmn/MC-Launcher-Alpha/releases) to download the latest version of MC Launcher Alpha.

Windows users should download `MC Launcher Alpha Setup x.x.x.exe` (NSIS installer).

## Installation

Run the downloaded `MC Launcher Alpha Setup x.x.x.exe` and follow the installation wizard to complete the setup.

MC Launcher Alpha will launch automatically after installation.

## Build from Source

```bash
git clone https://github.com/nnkmn/MC-Launcher-Alpha.git
cd MC Launcher Alpha
npm install
npm run dev
```

Build the installer package:

```bash
# Windows
npm run build:win
```

The build output is located in the `build/` directory.

## First Launch Checklist

After launching MC Launcher Alpha for the first time:

1. Go to the **Settings** page
2. Verify that the Java path is correct (auto-detection is supported)
3. Confirm the game directory (default is `.minecraft`, can be customized)
4. Go to the **Accounts** page and add an account
5. Go to the **Versions** page and install the desired version
6. Click **Launch**
