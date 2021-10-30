# Hackintosh Monterey Guide for HP 6300 Pro / HP Elite 8300 (OpenCore 0.7.4)

![Snapshot](images/snapshot.png)

### Hardware

Type|Item
:----|:----
**HDD** | SATA SSD
**GPU** | AMD RX560
**WiFi + BT Combo** | BCM943602CS + PCIe Adaptor

### Current Driver Versions
Driver Name|Version
:----|:----
Lilu | 1.5.6
WhateverGreen | 1.5.4
AppleALC | 1.6.5 (modified)
VirtualSMC | 1.2.7
IntelMausi | 1.0.7

## Instructions
### 1. Prepare installation media 
https://dortania.github.io/OpenCore-Install-Guide/extras/big-sur/  
https://dortania.github.io/OpenCore-Install-Guide/extras/monterey.html
### 2. Modify 'config.plist' for your own serial number, UUID, MLB, ROM, etc.
### 3. Copy 'BOOT' and 'OC' directories to the EFI partition of the USB disk.
### 4. Optional Settings
* Change SSDT.aml for CPU PM according to your own CPU. Current one is for i7 3770.
[See the Guide](https://github.com/Piker-Alpha/ssdtPRGen.sh)
* Configure IGPU if you don't use dGPU (IGPU has not been supported in Monterey).
* For nVidia Kepler GPU in Monterey, please refer to:
https://github.com/chris1111/Geforce-Kepler-patcher
* Configure NVMe if you use NVMe adaptor.

## References:
https://github.com/Sniki/HP6300-HP8300  
https://github.com/blacklizard/Hackintosh-Opencore-Guide-HP8300-SFF-i5-3470-Catalina

