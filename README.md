# Optimized Base-Game The Sims for Old 3DS

An optimized configuration and homebrew setup for running *The Sims* smoothly on Old 3DS hardware.

> **Important:** This repository does NOT contain any copyrighted game assets or data files. Users must supply their own legitimate game files.

---

## 📋 Installation Guide

### Step 1: Install the Homebrew Executable
1. Extract `Sims old 3DS.zip`.
2. Move `sims.3dsx` to the `/3ds/` folder on your SD card (`sdcard_root/3ds/sims.3dsx`).

### Step 2: Install the Luma3DS LayeredFS Performance Patch
1. Copy the `0004000000000000` folder from the zip file.
2. Paste it into your Luma titles directory: `sdcard_root/luma/titles/`.
3. Your final path on the SD card must look like this:
   `sdcard_root/luma/titles/0004000000000000/romfs/UserData/Options.iff`

### Step 3: Enable Game Patching
1. Power off your 3DS.
2. Hold down **SELECT** and turn on the 3DS to open the Luma3DS configuration menu.
3. Make sure **Enable game patching** is enabled `(x)`.
4. Press **START** to save and reboot.

### Step 4: Supply Game Data Files
1. Copy your extracted legitimate base game data files to your working game folder on the SD card.
2. **Performance Note:** Ensure Expansion Packs 1–7 are removed to maintain optimal performance and stability on Old 3DS systems.
