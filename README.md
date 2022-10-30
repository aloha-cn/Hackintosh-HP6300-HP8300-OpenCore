# Hackintosh Monterey / Ventura for HP 6300 Pro / HP Elite 8300 (OpenCore 0.8.5)

![Snapshot](images/snapshot.png)

### Hardware

Type|Item
:----|:----
**HDD** | Apple SSD (PCIe/Sata)
**GPU** | AMD RX560
**WiFi + BT Combo** | BCM943602CS + PCIe Adaptor

## Notes
1. For MacOS Ventura, SIP and Secure boot is disabled in the 'config.plist' since you'll need post installation. Please refer to: https://dortania.github.io/OpenCore-Legacy-Patcher/
2. For Moterey and older, please use the 'config.Pre-Ventura.plist', in which SIP is enabled.
3. Modify 'config.plist' for your own serial number, UUID, MLB, ROM, etc.
4. To use NVMe or Apple PCIe SSD, you have to use a USB disk for boot. Copy 'BOOT' and 'OC' directories to the EFI partition of the USB disk.
5. Optional Settings
* Change SSDT.aml for CPU PM according to your own CPU. Current one is for i7 3770.
[See the Guide](https://github.com/Piker-Alpha/ssdtPRGen.sh)
* Configure IGPU if you don't use dGPU.

## References:
https://github.com/Sniki/HP6300-HP8300  
https://github.com/blacklizard/Hackintosh-Opencore-Guide-HP8300-SFF-i5-3470-Catalina

