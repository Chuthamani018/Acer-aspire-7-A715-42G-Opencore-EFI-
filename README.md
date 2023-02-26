# Acer-aspire-7-A715-42G-Opencore-EFI-

#### Supports MacOS 11.6 >> Monterey 12.0 >> Ventura 13.0

<p align="center">
  <img src="https://raw.githubusercontent.com/Chuthamani018/Acer-aspire-7-A715-42G-Opencore-EFI-/main/ScreenShot/Spec.png" alt="Specs">
</p>

## Specs

|Model|Acer-aspire-7-A715-42G|
|---|---|
|CPU|AMD Ryzen 5 5500U|
|GPU|AMD Radeon(TM) Graphics|
|SSD|512 GB NVME.m2|
|RAM|8GB|
|Ethernet|Realtek RTL|
|Wifi Adapter|MediaTek Wi-Fi 6 MT7921 Wireless LAN Card|
|Bluetooth|MediaTek Bluetooth MT7921|
|Keyboard|ps2 keyboard|
|Trackpad|I2C Elan 0504|

## Working Status

- [x] Dual boot Windows 10 + MacOS BigSur
- [x] Ethernet
- [x] USB2.0 ports
- [x] Usb 3.0 + Type C

 ### Known Issues
- Battery life is just half of what I get in windows 
- SK Hyinx NVme Cause Kernel Panic on Mac OS

### Not Tested

- [x] Webcam

## Installation 

### BIOS Settings

- Will Put Soon

###  Basic Installation

- Create a Bootable USB for MacOS by using by Dortania's [OpenCore-Install-Guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/).
- Install MacOS to SSD / Hard drive. (While installing, connect USB keyboard and mouse).
- Copy **ALL** the Contains of this Repo inside the EFI partition of SSD / Hard drive.
- **[IMPORTANT]** Make sure to Generate system definitions of MacBook pro 15,4 in config.plist file using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) & add `SystemSerialNumber`, `SystemUUID` and `MLB`.



<p align="center">
<b>⭐ Please consider starring this repository if it helped you! ⭐</b>
</p>
