# Deadbug Labs

**IMP-1** — a portable hardware exploration device, designed and
built from salvaged electronics. No commercial dev kits.

This repository is the project site: `index.html` is served as-is by GitHub
Pages (no build step).

## Status — 2026-11-19

- **Firmware:** clean build — 0 errors, 0 warnings (ESP32-S3, 12 tools).
- **Boards:** main board v10 routing — braid re-lay pass complete
  (23 → 20 unconnected nets, 0 clearance violations, 0 shorts); NFC board
  DRC-clean; IR board routing done. Gate 3 (PCB integrity) has not
  passed yet: the remaining nets are sealed at placement level, and a
  targeted hand micro-work pass is next. Nothing fabricated yet.
- **IMP-VISION:** new product line — AI smart glasses (glasses + phone,
  no hub). The companion app v0 is built and running on a phone: a model
  picker over a 1,242-model catalog, ready-made model sets, and
  on-device answers via a local model.

## Hardware

- ESP32-S3 (native USB)
- ST25R3916B NFC front-end
- CC1101 Sub-GHz radio
- 1.47" 172x320 colour display
- Socketed SPI flash with a physical write-protect lock
- microSD
- 2x 18650 (1S2P, 25.9 Wh)
- Salvaged Uniden Stealth LRD 767 shell

## Firmware

The 12-tool ESP32-S3 firmware lives in its own repository:
[github.com/deadbuglabs/imp-1](https://github.com/deadbuglabs/imp-1)

## Links

- [DeadbugLabs on Facebook](https://www.facebook.com/profile.php?id=61591927232914)
- Sponsorship: PCBWay has granted Deadbug Labs a USD 30 3D-print credit
  (no expiry; held until the boards are fabricated and fit-checked).
  PCB/assembly sponsorship for the first fabrication run is still open.

— Deadbug Labs

Contact / orders: imp-ai@muse.ai
