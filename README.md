# ESP32 Marauder Web GUI

A modern **Web GUI for the ESP32 Marauder**, designed to interact with the device directly from your browser using the **Web Serial API**.
This interface gives you easy access to WiFi, Bluetooth, Sniffing, Attack, GPS, and System tools — all from a simple and responsive web dashboard.

> View my site : [Get Link](https://pranav-v-20.github.io/ESP32-Marauder-Web-GUI/)

---

## ✨ Features

* 📡 **WiFi Tools** – Scan APs, list devices, deauth, ARP scan, ping scan.
* 🟦 **Bluetooth Tools** – BLE sniffing, spamming, wardriving.
* 👀 **Sniffing** – Capture raw packets, PMKID, and deauth frames.
* ⚡ **Attacks** – Launch probe floods, deauths, and rickroll WiFi prank.
* 🌐 **Evil Portal** – Create and serve a captive portal with custom HTML.
* 📍 **GPS Support** – Get live GPS data, satellites, and wardrive logs.
* ⚙️ **System Controls** – Reboot, view system info, list filesystem.
* 🖥️ **Interactive Terminal** – Real-time output from ESP32 with scrollback.
* ⌨️ **Command Input Box** – Send any command manually via textbox + Enter key.

---

## 🖼️ GUI Preview

```
┌───────────────────────────────────────┐
│              ESP32 Marauder           │
│ ─────────────── Sidebar ───────────── │
│ 📡 WiFi                                │
│ 🟦 Bluetooth                           │
│ 👀 Sniffing                            │
│ ⚡ Attacks                             │
│ 🌐 Evil Portal                         │
│ 📍 GPS                                 │
│ ⚙️ System                              │
│ 🔌 Connect                             │
└───────────────────────────────────────┘

[ Terminal Output Here ]  
[ Command Input Box + Enter Button ]
```

<img width="1919" height="1022" alt="Screenshot 2025-08-19 213404" src="https://github.com/user-attachments/assets/cdcfed38-6e9e-4c93-ad93-24c8713669a0" />

---

## 🚀 Getting Started

### 1. Requirements

* ESP32 device with **ESP32 Marauder firmware** flashed.
* Modern browser with **Web Serial API support** (Chrome, Edge, Brave).
* USB cable to connect ESP32 to your computer.

### 2. Usage

1. Clone this repo or download the HTML file.
2. Open the file in a browser (no server needed).
3. Click **🔌 Connect** and select your ESP32 device.
4. Use the sidebar to navigate between tools.
5. Watch the output in the terminal.
6. Enter custom commands in the input box and hit **Enter**.

---

## ⚡ Command Input

Below the terminal, you’ll find a **command input box**.

* Type your command manually and press **Enter** or click the ▶ **Enter button**.
* Example:

  ```
  scanap
  attack deauth
  ls /
  info
  ```

---

## 🔒 Disclaimer

This project is for **educational and security research purposes only**.
Do **not** use it against networks, devices, or systems you don’t own or have explicit permission to test.
The author is not responsible for misuse.

