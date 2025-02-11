# Flipper Zero: Flashing, Wi-Fi, Custom Animations & Mods  

A **complete guide** for **Flipper Zero firmware flashing, Wi-Fi Dev Board setup, custom animations, and mods**.  
Includes **separate Mac & Windows sections** and links to **GitHub repositories** for advanced tools.  

---

## 📌 Table of Contents  

- [Flipper Zero Overview](#flipper-zero-overview)  
- [Firmware Options](#firmware-options)  
- [Flashing Tools (Mac & Windows)](#flashing-tools-mac--windows)  
- [Flashing Guide - Windows](#flashing-guide---windows)  
- [Flashing Guide - Mac](#flashing-guide---mac)  
- [Wi-Fi Dev Board Overview](#wifi-dev-board-overview)  
- [Wi-Fi Dev Board Setup - Windows](#wifi-dev-board-setup---windows)  
- [Wi-Fi Dev Board Setup - Mac](#wifi-dev-board-setup---mac)  
- [Wi-Fi Board Firmware Options](#wifi-board-firmware-options)  
- [Creating Custom Animations](#creating-custom-animations)  
- [Custom UI & Themes](#custom-ui--themes)  
- [Applications & Plugins](#applications--plugins)  
- [Community & Support](#community--support)  
- [Final Notes](#final-notes)  

---

## 📌 Flipper Zero Overview  

Flipper Zero is a **multi-tool for digital access systems**. It includes:  

✔ **Sub-GHz** – Analyze and replay RF signals.  
✔ **NFC & RFID** – Read, write, and emulate NFC tags.  
✔ **Infrared (IR)** – Universal remote for TVs and other IR devices.  
✔ **GPIO & UART** – Interface with hardware.  
✔ **Bluetooth & HID** – Wireless communication and HID injection.  
✔ **Wi-Fi (with Dev Board)** – Wireless debugging and network testing.  

---

## 🎨 Creating Custom Animations  

Want to create a **custom boot animation** for your Flipper Zero? Follow these steps:  

### Tools Needed:  
✔ **Flipper Zero Animation Toolkit** → [Download](https://github.com/Flipper-Devices/flipperzero-animation)  
✔ **Python** (for script-based animation creation) → [Python Download](https://www.python.org/downloads/)  

### Steps:  

1. **Convert images to Flipper-compatible format:**  
   ```sh
   python convert.py --input image.png --output animation.flp
**Move the animation file to** `/assets/animations/` **on your Flipper Zero.**  
**Reboot and enjoy your custom animation!**  

---

## 🎨 Custom UI & Themes  

Want to customize Flipper Zero’s **UI & icons**?  

✔ **Flipper Theme Collection** → [Download](https://github.com/flipperdevices/flipperzero-theme)  
✔ **Custom Menu Icons** → [Download](https://github.com/UberGuidoZ/Flipper)  

---

## 📲 Applications & Plugins  

| App | Purpose | Download |
|-----|---------|----------|
| **Flipper-Apps** | Extra utilities, games, and scripts | [Download](https://github.com/FlipperApps/Flipper-Apps) |
| **Xtreme Apps Pack** | Large collection of mods | [Download](https://github.com/FlipperApps/XtremeApps) |
| **Sub-GHz Expanded** | More RF frequencies & tools | [Download](https://github.com/UberGuidoZ/Flipper) |
| **NFC Tools** | Enhanced NFC reading/writing | [Download](https://github.com/flipperdevices/nfc) |

---

## 🌎 Community & Support  

- **[Flipper Zero Docs](https://docs.flipperzero.one/)** – Official Documentation  
- **[Flipper Zero Discord](https://discord.gg/flipperzero)** – Community Support  
- **[Flipper Zero Forum](https://forum.flipperzero.one/)** – Discussions & Troubleshooting  

---

## ⚡ Final Notes  

This guide provides a **complete overview** of **Flipper Zero firmware flashing, Wi-Fi Dev Board setup, custom animations, and modifications**.  

For troubleshooting and advanced modifications, refer to the **community resources** above.  
