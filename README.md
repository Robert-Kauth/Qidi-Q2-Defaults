# QIDI Q2 Firmware Reference

This repository tracks package-owned files shipped in QIDI Q2 firmware. Use tags and commit history to compare package revisions.

## Scope

- `config/`: QIDI's shipped Klipper, Moonraker, macro, Box, and preset configuration (`/home/mks/printer_data/config/`).
- `klipper/klippy/`: the complete package-owned `/home/mks/klipper/klippy/` tree, including Python, C, and shared-object files.
- `moonraker/moonraker/`: the package-owned `/home/mks/moonraker/moonraker/` tree.
- `firmware-package.json`: the release archive, SOC package, and board image names and SHA-256s.
- `config/saved_variables.cfg.bak` isn't tracked.
- These files are reference material for QIDI's shipped firmware, not a drop-in profile for another machine.

## Source

QIDI's release asset `Q2_V1.1.1.zip` from https://github.com/QIDITECH/QIDI_Q2/releases, extracted from the SOC Debian package with `dpkg-deb -x`. QIDI's files are GPLv3; see LICENSE.
