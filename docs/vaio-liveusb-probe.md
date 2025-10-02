# VAIO Live USB Probe — VGN-NS110E

## CPU Architecture
- `uname -m` → `x86_64` (64-bit confirmed)

## Memory
- `free -h` → ~1.8 GiB usable (2 GB installed)

## Storage (lsblk)
- `sda` → 149.1G (internal 160 GB HDD)
- `sdb` → 7.5G (8 GB Lubuntu installer USB)

## Networking (lspci | grep -i net)
- Ethernet controller: Marvell (detected)
- Wireless controller: Qualcomm Atheros AR928X (good Linux support)

## Status
- Keyboard, touchpad, USB working in Try Lubuntu
- Clear to proceed with install (Erase disk and install)
