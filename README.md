# Optimized Base-Game The Sims for Old 3DS

An optimized configuration and homebrew setup for running *The Sims* smoothly on Old 3DS hardware.

> **Important:** This repository does NOT contain any copyrighted game assets or data files. Users must supply their own legitimate game files.

---

## 📋 Installation Guide

### Step 1: Generate Game Files
1. Visit the **Sims 3DS Builder** website.
2. Insert and upload/drag all **4 PC installation discs** into the web builder tool to generate the processed game assets.
3. Download the generated output files.

### Step 2: Install Homebrew & Luma Patch
1. Download `Sims.old.3DS.zip` from the **Releases** page.
2. Extract the zip file on your computer.
3. Move `sims.3dsx` to the `/3ds/` folder on your SD card (`sdcard_root/3ds/sims.3dsx`).
4. Copy the `0004000000000000` folder into your Luma titles directory (`sdcard_root/luma/titles/`).
   * *Verification:* Your final path must be `sdcard_root/luma/titles/0004000000000000/romfs/UserData/Options.iff`.

### Step 3: Enable Game Patching & Add Files
1. Power off your 3DS. Hold **SELECT** while turning it on to open the Luma3DS configuration menu.
2. Ensure **Enable game patching** is checked `(x)`, then press **START** to save and reboot.
3. Place your generated base game files into your working game directory on the SD card.
4. **Performance Note:** Ensure Expansion Packs 1–7 are removed to maintain smooth frame rates on Old 3DS hardware.
