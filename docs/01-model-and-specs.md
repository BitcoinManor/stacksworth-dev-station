# VAIO Model & Specs

## Identification
- Model number: **PCG-7142L**
- Series: Sony VAIO NS series
- Original OS: Windows Vista

## To Capture (from Live USB later)
- `uname -a`
- `lscpu`
- `free -h`
- `lsblk -o NAME,SIZE,TYPE,MOUNTPOINT`
- `sudo lshw -short | head -n 50`
- `lspci | grep -i net`
- `lsusb`

## Baseline Notes
- Memory type: DDR2 SO-DIMM (to confirm max capacity)
- Likely max RAM: 4 GB (2 × 2 GB)
- Drive interface: 2.5″ SATA
- Next step: boot Live USB and capture results
