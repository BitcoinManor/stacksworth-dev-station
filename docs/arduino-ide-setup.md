# Arduino IDE Setup on VAIO Dev Station

## Download
- Downloaded **Arduino IDE 2.3.6 Linux Zip (x86-64)** from [arduino.cc](https://www.arduino.cc/en/software).
- Saved to `~/Downloads`.

## Install
```bash
unzip ~/Downloads/arduino-ide_2.3.6_Linux_64bit.zip -d ~/Downloads/
sudo mv ~/Downloads/arduino-ide_2.3.6_Linux_64bit /opt/arduino-ide
sudo ln -s /opt/arduino-ide/arduino-ide /usr/local/bin/arduino-ide
Sandbox Fix
sudo chown root:root /opt/arduino-ide/chrome-sandbox
sudo chmod 4755 /opt/arduino-ide/chrome-sandbox

Launch
arduino-ide


First launch confirmed working.

Icon pinned to Lubuntu panel for quick access.
