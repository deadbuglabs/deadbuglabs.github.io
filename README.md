# Deadbug Labs

**IMP-1** — a Flipper-class portable hardware exploration device, designed and
built from salvaged electronics. No commercial dev kits.

This repository is the project site: `index.html` is served as-is by GitHub
Pages (no build step).

## Status — 2026-11-16

- **Firmware:** clean build — 0 errors, 0 warnings (ESP32-S3, 12 tools).
- **Boards:** in layout — main board in respin, NFC board in final routing,
  IR board complete. Nothing fabricated yet; fabrication is gated on a clean
  design-rule check.

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
- Hardware sponsorship: open — IMP-1 is seeking PCB/assembly sponsorship for
  its first fabrication run.

— Deadbug Labs
