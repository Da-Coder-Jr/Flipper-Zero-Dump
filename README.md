# 🛠 Flipper Zero: Complete Guide (Flashing, Wi-Fi, Custom Animations & More)  

> **[!IMPORTANT]**  
> This guide provides **everything you need** for **Flipper Zero**, including **flashing firmware, Wi-Fi Dev Board setup, creating custom animations, and installing mods.**  
> It is designed for **Windows & macOS** users with **step-by-step instructions** and **verified repositories.**  

---

## 📌 Table of Contents  

- [Flipper Zero Overview](#flipper-zero-overview)  
- [Firmware Options](#firmware-options)  
- [Flashing Tools (Mac & Windows)](#flashing-tools-mac--windows)  
- [Flashing Guide - Windows](#flashing-guide---windows)  
- [Flashing Guide - Mac](#flashing-guide---mac)  
- [Wi-Fi Dev Board Setup](#wifi-dev-board-setup)  
- [Creating Custom Animations](#creating-custom-animations)  
- [Custom UI & Themes](#custom-ui--themes)  
- [Applications & Plugins](#applications--plugins)  
- [Community & Support](#community--support)  
- [Final Notes](#final-notes)  

---

## 🔹 Flipper Zero Overview  

Flipper Zero is a **multi-tool for digital access systems**, allowing you to interact with:  

✔ **Sub-GHz** – Capture and replay RF signals.  
✔ **NFC & RFID** – Read, write, and emulate tags.  
✔ **Infrared (IR)** – Universal remote for TVs & devices.  
✔ **GPIO & UART** – Hardware debugging and interaction.  
✔ **Bluetooth & HID** – Wireless device communication.  
✔ **Wi-Fi (with Dev Board)** – Wireless testing and debugging.  

---

## 🔧 Firmware Options  

| Firmware | Features | Download |
|----------|----------|----------|
| **Official (OFW)** | Stable, regularly updated | [Download](https://flipperzero.one/update) |
| **Unleashed** | Unlocks regional limits, extra tools | [Download](https://github.com/DarkFlippers/unleashed-firmware) |
| **Momentum** | Enhanced UI, more security tools | [Download](https://github.com/MomentumMod/Momentum) |
| **RogueMaster** | Largest app & plugin collection | [Download](https://github.com/RogueMaster/flipperzero-firmware-wPlugins) |

---

## 💾 Flashing Tools (Mac & Windows)  

| Tool | Platform | Download | Purpose |
|------|----------|----------|---------|
| **qFlipper** | Windows & macOS | [Download](https://flipperzero.one/update) | Official flashing tool |
| **Flipper Firmware Updater** | Windows & macOS | [Download](https://github.com/flipperdevices/qFlipper/releases) | Alternative flashing method |
| **ESPHome Flasher** | Windows & macOS | [Download](https://github.com/esphome/esphome-flasher/releases) | Flashing Wi-Fi Dev Board |

---

## 🖥 Flashing Guide - Windows  

1. **Download and install qFlipper** → [Download](https://flipperzero.one/update).  
2. **Connect Flipper Zero** via USB.  
3. **Open qFlipper** and go to **"Update Firmware"**.  
4. **Select firmware** (Official, Unleashed, Momentum, or RogueMaster).  
5. **Click Flash** and wait for the process to complete.  
6. **Restart your Flipper Zero** and confirm the update.  

---

## 💻 Flashing Guide - Mac  

1. **Download and install qFlipper** → [Download](https://flipperzero.one/update).  
2. **Connect Flipper Zero** via USB-C.  
3. **Open qFlipper**, select your device, and click **"Update Firmware"**.  
4. **Choose firmware** (Official, Unleashed, Momentum, or RogueMaster).  
5. **Flash the firmware** and wait for completion.  
6. **Restart your Flipper Zero** and verify installation.  

---

## 📶 Wi-Fi Dev Board Setup  

1. **Download Wi-Fi Dev Board firmware** → [Download](https://github.com/0xchocolate/flipperzero-wifi-devboard).  
2. **Use ESPHome Flasher** to install firmware.  
3. **Connect Flipper Zero to Wi-Fi board** via GPIO.  
4. **Open Flipper's serial console** and confirm connection.  

---

## 🎨 Creating Custom Animations  

Want to create a **custom boot animation** for your Flipper Zero?  

### 🔹 Tools Needed  
✔ **Flipper Zero Animation Toolkit** → [Download](https://github.com/Flipper-Devices/flipperzero-animation)  
✔ **Python** (for script-based animation creation) → [Download](https://www.python.org/downloads/)  

### 🔹 Steps  

1. **Convert images to Flipper-compatible format:**  
   ```sh
   python convert.py --input image.png --output animation.flp
   ```  
2. **Move the animation file to** `/assets/animations/` **on your Flipper Zero.**  
3. **Reboot and enjoy your custom animation!**  

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

> **[!WARNING]**  
> This guide is **regularly updated** to include the **latest tools & firmware**.  
> If you encounter any issues, refer to the **community support links above**.  

This guide provides a **complete overview** of **Flipper Zero firmware flashing, Wi-Fi Dev Board setup, custom animations, and modifications**.  

For troubleshooting and advanced modifications, refer to the **community resources** above.  
