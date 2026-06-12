# KITT device firmware

Official **firmware binaries** for the KITT road copilot (ESP32 CYD).  
Installed over Bluetooth from the **KITT** iPhone app.

This repository contains **releases only** — no source code.  
Tags look like `device-v0.0.5`.

## Assets per release

| File | Purpose |
|------|---------|
| `device_firmware.bin` | CYD application image (BLE OTA) |
| `device_firmware.sha256` | SHA-256 hex digest for verification |

## Install

1. Pair KITT in the iOS app.
2. **Advanced** → **Check for updates** → **Update**.
3. Keep the phone near the device until KITT restarts.

Firmware **≥ 0.0.3** is required for app-based updates (first install may need USB flash from the manufacturer).

## Privacy

- This repo is **public** (binaries only).
- KITT iOS app and firmware **source** are private and not published here.