# 02 — Lubuntu 24.04 LTS Install on VAIO Dev Station

This document records the steps taken to install Lubuntu 24.04 LTS (minimal) on the Sony VAIO PCG-7142L.

## Pre-Install BIOS Setup
- Powered on the VAIO and pressed **F2 repeatedly** to enter the BIOS.  
- In the **Boot tab** (navigated with arrow keys):  
  - Enabled **Boot from external device**.  
  - Changed **Boot order** so that USB came first.  
- Saved changes and rebooted with Lubuntu USB installer inserted.  

## Installation Steps
1. Booted from USB installer.  
2. Selected **Normal Installation**.  
3. Partitioning:  
   - Chose **Erase Disk**.  
   - Selected **Swap to File**.  
   - File system: **ext4**.  
   - Bootloader: **Master Boot Record of TOSHIBA MK165SX (/dev/sda)**.  
4. User setup: entered full name, username, computer name, password.  
5. Installation proceeded successfully.  

## First Boot Verification
- Confirmed architecture: `x86_64`.  
- RAM: ~1.8 GiB.  
- Drives: `sda` (149 GB HDD), `sdb` (USB installer).  
- Network controllers detected: Marvell (wired), Qualcomm Atheros AR928X (WiFi).  

## Notes
- Installer warned some requirements not met, but system runs.  
- SSD + RAM upgrade planned.  
