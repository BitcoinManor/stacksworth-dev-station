# 04 — Browser Setup on Lubuntu (VAIO)

After first boot of Lubuntu 24.04 (minimal), no browser was installed. Attempting to install Firefox revealed issues.

## Snap Firefox Problems
- `apt install firefox` pulls in the Snap version by default.  
- On the VAIO (HDD + low RAM), Snap Firefox was extremely slow.  
- First run appeared frozen and opened unwanted default tabs.  
- Conclusion: Snap Firefox is not viable on this hardware.

## Next Steps
- Plan: remove Snap Firefox completely.  
- Replace with Google Chrome (.deb) for consistency with other devices.  
- Chromium (from Ubuntu repos) is an alternative if Chrome proves too heavy before RAM/SSD upgrade.  
