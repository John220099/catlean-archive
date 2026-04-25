# Catlean Client Archive

> **Archive Repository**: This repository hosts legacy versions of the Catlean Minecraft client that are no longer available for download elsewhere.

## About

This archive contains older versions of Catlean Client recovered from local storage. Since historical versions aren't available through official channels, this repository serves as a preservation effort for users who need specific legacy releases.

## Table of Contents
- [Available Versions](#available-versions)
- [Installation Guide](#installation-guide)
- [Troubleshooting](#troubleshooting)
- [Additional Resources](#additional-resources)

## Available Versions

| Version | Minecraft Version | Download |
|---------|-------------------|----------|
| 0.0.2   | 1.21.4           | [Download](https://github.com/John220099/catlean-archive/raw/refs/heads/main/catlean-1.21.4-0.0.2.jar) |
| 0.0.3   | 1.21.4           | [Download](https://github.com/John220099/catlean-archive/raw/refs/heads/main/catlean-1.21.4-v0.0.3.jar) |
| 0.0.5   | 1.21.4           | [Download](https://github.com/John220099/catlean-archive/raw/refs/heads/main/catlean-1.21.4-v0.0.5.jar) |
| 0.0.7   | 1.21.4           | [Download](https://github.com/John220099/catlean-archive/raw/refs/heads/main/catlean-1.21.4-v0.0.7.jar) |
| 0.0.8   | 1.21.4           | [Download](https://github.com/John220099/catlean-archive/raw/refs/heads/main/catlean-1.21.4-v0.0.8.jar) |
| 0.1.0   | 1.21.9           | [Download](https://github.com/John220099/catlean-archive/raw/refs/heads/main/catlean_1.21.9-v0.1.0.jar) |
| 0.1.2   | 1.21.11          | [Download](https://github.com/John220099/catlean-archive/raw/refs/heads/main/catlean_1.21.11-v0.1.2.jar) |

> ⚠️ **Note**: These are archived versions. For the latest release, please visit the official Catlean repository.

---

## Installation Guide

### Prerequisites
- Minecraft Java Edition installed
- Java Runtime Environment (JRE) compatible with your Minecraft version
- The Catlean `.jar` file downloaded from the table above

### Step 1: Install Fabric Loader
Download and install the Fabric Loader for your Minecraft version:
1. Visit [Fabric's official website](https://fabricmc.net)
2. Download the installer for your operating system
3. Run the installer and select your Minecraft version (match it to the Catlean version you downloaded)
4. Click "Install" to complete the setup

### Step 2: Download Required Dependencies
You'll need two core dependencies for Catlean to work:

**Fabric API**
- Download from [Modrinth - Fabric API](https://modrinth.com/mod/fabric-api)
- ⚠️ Make sure to get the version matching your Minecraft version

**Fabric Language Kotlin**
- Download from [Modrinth - Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin)
- ⚠️ Ensure compatibility with your Minecraft version

### Step 3: Install the Mods
1. **Locate your `.minecraft` folder:**
   - **Windows**: Press `Win + R`, type `%APPDATA%\.minecraft`, press Enter
   - **macOS**: Press `Cmd + Shift + G`, type `~/Library/Application Support/minecraft`
   - **Linux**: `~/.minecraft`

2. **Navigate to the `mods` folder**
   - If the folder doesn't exist, create it

3. **Place the following `.jar` files into the `mods` folder:**
   - ✅ Catlean Client (the version you downloaded)
   - ✅ Fabric API
   - ✅ Fabric Language Kotlin

### Step 4: Launch the Game
1. Open the Minecraft Launcher
2. Select the **Fabric** profile from the dropdown menu
3. Click **Play**
4. Verify Catlean is loaded by checking the mods menu in-game

---

## Troubleshooting

### Game crashes on startup
- Verify all mods are compatible with the **same Minecraft version**
- Check that you have the latest version of Fabric API and Fabric Language Kotlin for your MC version
- Remove other mods temporarily to identify conflicts

### Mods not loading
- Ensure all `.jar` files are in the correct `mods` folder
- Check that Fabric Loader is properly installed (you should see "Fabric" in the launcher profiles)
- Verify you're launching the Fabric profile, not vanilla Minecraft

### Version compatibility issues
- Match the Catlean version's Minecraft version exactly (e.g., Catlean 0.0.8 requires MC 1.21.4)
- Download the corresponding Fabric Loader, Fabric API, and Fabric Language Kotlin for that MC version

---

## Additional Resources
- [Fabric Documentation](https://fabricmc.net/wiki/)
- [Modrinth Help Center](https://docs.modrinth.com/)
- [Minecraft Mods Troubleshooting Guide](https://fabricmc.net/wiki/tutorial:troubleshooting)

---

## Disclaimer
This is an unofficial archive. These versions are provided as-is for preservation purposes. Always use the latest official release when possible for security and stability.
