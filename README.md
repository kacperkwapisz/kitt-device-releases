# KITT device firmware

Official **firmware binaries** for the **KITT** road copilot display.  
Installed over Bluetooth from the **KITT** iPhone app.

This repository contains **releases only** — no source code.  
Tags look like `device-v0.1.0`.

## Assets per release

| File | Purpose |
|------|---------|
| `device_firmware.bin` | KITT device application image (BLE OTA) |
| `device_firmware.sha256` | SHA-256 hex digest for verification |

## Install

1. Pair your KITT in the iOS app.
2. **Advanced** → **Check for updates** → **Update**.
3. Keep the phone near the device until KITT restarts.

Firmware **≥ 0.0.3** is required for app-based updates (first install may need USB from the maintainer).

## Privacy

- This repo is **public** (binaries only).
- The KITT iOS app and firmware **source** are private and not published here.