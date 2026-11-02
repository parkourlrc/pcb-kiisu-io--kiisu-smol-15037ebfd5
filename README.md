# KIISU SMOL

> **Modular & Small like never before!**

Hardware design files, schematics, and 3D models for **KIISU SMOL** — a modular networking development board built around the STM32WB55 with Flipper Zero firmware compatibility and pluggable expansion modules for Wi-Fi, GPS, LoRa (Meshtastic), NFC and RFID.

<p align="center">
  <img src="https://kiisu.io/wp-content/uploads/2026/04/kiisu-smol-full-set-1536x864.png" alt="KIISU SMOL with modular add-ons" width="720">
</p>

## 🚀 Now on Indiegogo

KIISU SMOL is currently crowdfunding. Back the campaign and get yours:

**👉 [Support on Indiegogo](https://www.indiegogo.com/projects/rainwalker/kiisu-smol---networking-development-board)**

## Highlights

- **Main MCU:** STM32WB55RGV / STM32WB55VGY (Cortex-M4, 64 MHz, 1 MB flash, 256 KB RAM)
- **Sub-GHz:** CC1101 (300–348 / 387–464 / 779–928 MHz)
- **NFC:** ST25R3916 (13.56 MHz, ISO14443 / ISO15693)
- **RFID:** 125–132 kHz
- **Bluetooth:** built-in with antenna
- **IR:** receiver and transmitter
- **Display:** 128×64 OLED (SSD1306-compatible)
- **GPIO:** 2×12-pin, 2.54 mm pitch, Flipper Zero pin-compatible
- **Storage:** soldered 512 MB SD
- **Power:** USB-C, LiPo connector, on-board 5 V → 3.3 V LDOs

### Expansion modules

- **Dual-Band Wi-Fi / GPS / SD** (ESP32-C5)
- **LoRa** (Meshtastic-compatible, SMA connector)
- **NFC / RFID + LIR2032** add-on

## Repository contents

| File / Folder | Description |
|---|---|
| `kiisu smol v1a schematics.pdf` | KIISU SMOL V1a schematics |
| `kiisu smol v1a model.step` / `.glb` | 3D model of the main board |
| `kiisu smol kicad extension board/` | Sample KiCad project (CR2032 expansion board) and 3D packages |

## Firmware

- **Main firmware** (Flipper Zero–compatible): [`kiisu-smol-firmware`](https://github.com/kiisu-io/kiisu-smol-firmware)

## Where to buy

- **Direct (EU):** https://store.rainwalker.ee/
- **Indiegogo (worldwide):** https://www.indiegogo.com/projects/rainwalker/kiisu-smol---networking-development-board

## Community

- 💬 Discord — https://discord.gg/kiisu
- 📰 Reddit — https://www.reddit.com/r/KIISU_IO/
- ✈️ Telegram — https://t.me/kiisu_io
- 📸 Instagram — https://instagram.com/kiisu.io
- 📘 Facebook — https://facebook.com/profile.php?id=61576595588296

## License

Hardware design files (schematics, PCB project, 3D models) are released under the **[CERN Open Hardware Licence Version 2 — Strongly Reciprocal (CERN-OHL-S v2)](LICENSE)**.

The hardware design is open only to the extent published in this repository:

- **KIISU SMOL main board** — schematics as a PDF document and a 3D model. The original CAD sources (schematic and PCB layout projects) of the main board are not published, are not part of the licensed material and are not available on request.
- **Sample extension board** (`kiisu smol kicad extension board/`) — complete KiCad project, intended as a starting point for your own expansion modules.

Documentation, manuals and this README are released under the **[Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE-DOCS)**.

> Note: the previous internal name of this board was *Kiisu Mini*. Some artifacts in the KiCad sample project (`km-2032`, `kiisumini.step`, etc.) still carry the legacy `km` / `kiisumini` prefix to preserve internal references.

---

Made with ♥ by [RainWalker OÜ](https://kiisu.io/) · Tallinn, Estonia
