# 💻 Clevo N850/N8xEJEKHackintosh EFI - macOS Sonoma
Opencore Bootloader for Clevo N8xEJEK / N8x series laptop (N850/N8xEJEK/N8xxx)

This repository contains the EFI configuration for the Clevo N850 (N8xEJEK) laptop, optimized for macOS Sonoma.

## 🖥️ System Specifications

- **Model:** Clevo N8xEJEK (N850 Newer Model)
- **CPU:** Intel Core i7-8750H
- **GPU:** Intel UHD Graphics 630 (dGPU GTX 1050 Ti SSDT disabled)
- **Audio:** Realtek ALC269VC
- **Wi-Fi:** Intel Wireless-AC 9462
- **macOS Version:** Sonoma 14.7.4

## ✅ Functionality/What's Working

- [x] Intel UHD Graphics with full acceleration
- [x] Audio via AppleALC (Layout ID: 3)
- [x] Trackpad with basic gestures
- [x] Brightness control with slider and hotkeys
- [x] Battery status monitoring
- [x] Sleep and wake functionality
- [x] USB ports mapped correctly
- [x] Native NVRAM support
- [x] Bluetooth
- [x] AirDrop( Not Tested Yet)
- [x] Many more features not tested yet!

## ⚠️ Known Issues

- ❌ Trackpad dosen't support multi-touch gestures
- ❌ dGPU (GTX 1050 Ti) SSDT disabled due to lack of macOS support

## 🔧 Installation Instructions

1. **Backup:** Ensure you have backups of your data.
2. **Download Macos Sonoma RAW IMAGE:** You can download MacOs Sonoma 14.7.4 RAW torrent file from the release section
3. **Create Bootable USB:** Use BalenaEtcher to create a bootable USB.
4. **Replace EFI:** Copy the contents of this repository's `EFI` folder to the EFI partition of your USB drive. (I Recommend DiskGenius)
5. **Configure SMBIOS:** Use OCAT(https://github.com/ic005k/OCAuxiliaryTools) to generate unique serial numbers and update `config.plist`.
6. **BIOS Settings:** Adjust BIOS settings as necessary (e.g., disable Secure Boot, MAKE SURE YOU ENABLE AHCI).
7. **Install macOS:** Boot from the USB and follow the macOS installation process.
8. **Post-Installation:** Mount the EFI partition of your macOS drive and copy the EFI folder to it.

## 📸 Screenshots

![About This Mac](coming soon)
![System Information](coming soon)

## ✅ EFI COMPATIBILITY
This EFI Is only & currently compatible with Sonoma 14.7.4

## ⚠️ FIXES
To configure RGB keyboard light use https://www.mediafire.com/file/qp7aamd63shlgnv/Devastator+Led+Tool.dmg/file

## 🙏 Acknowledgments

- [Dortania OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [AppleALC](https://github.com/acidanthera/AppleALC)
- [Lilu](https://github.com/acidanthera/Lilu)
- [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [itlwm](https://github.com/OpenIntelWireless/itlwm)

---

> **Disclaimer:** Use this EFI at your own risk. Ensure you have backups and understand the Hackintosh process.
> The EFI Works perfectly on this version of Sonoma 14.7.4
> Next is MacOs Sequioa. STAY TUNED.
