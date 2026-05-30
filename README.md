# Ryzentosh EFI for Lenovo Ideapad gaming 3 (15ACH6)
<img width="1920" height="1080" alt="Screenshot 2026-05-29 at 1 53 24 PM" src="https://github.com/user-attachments/assets/6dccc8b1-5095-4c44-b4c9-392bbb847ae4" />


<div id="badges" align="center">
  <img src="https://img.shields.io/badge/OC-1.0.7-blue">
  <img src="https://img.shields.io/badge/macOS-Tahoe_26.5-blue">
</div>

# Specifications

| Item  | Info  |
| ------------ | ------------ |
| CPU  |  AMD Ryzen 5 5600H |
| IGPU  |  AMD Radeon Vega 7 |
| DGPU | NVIDIA GeForce RTX 3050 Ti  |
| SSD | WDC PC SN530 - 512GB  |
| WIFI | Realtek RTL8852AE  |
| Ethernet  | Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  |
| SMBIOS used  | MacBookPro 16,2 (Regenerate the SMBIOS with the **same macbook model**)  |

# What's Working

| Item | Status | Notes |
| --- | --- | --- |
| CPU | ✅ | Using latest AMD Vanilla patches |
| IGPU | ✅ | NootedRed.kext |
| Brightness Control | ✅ | Native Keys (F5/F6) |
| USB | ✅ | Currently Using USBInjectAll.kext |
| Keyboard | ✅ | VoodooPS2Controller.kext |
| Audio | ❌ | AppleHDA missing, requires external patches |
| Microphone | ❌ |  |
| Trackpad | ✅ | VoodooI2C.kext |
| Ethernet | ✅ | RealtekRTL8111.kext [**v2.4.2**](https://github.com/Mieze/RTL8111_driver_for_OS_X/issues/90) |
| Shutdown/Reboot | ✅ |   |

# What's not Working

| Item | Status | Notes |
| --- | --- | --- |
| Sleep | ❓ | |
| HDMI A/V out | ❓ | Not Tested Yet |
| DGPU | ❌ | RTX 3050Ti is NOT supported |
| Wi-Fi | ❌ | RTL8522AE not supported |
| Bluetooth | ❌ |  |
| AirDrop | ❌ |  |

# Bios Options

*   Secure Boot : **Disabled**
*   Boot Type : **UEFI**


# VERY IMPORTANT !

*   Verbose Mode Disabled by Default

*   Increase your VRAM size for better and smooth experience (512 MB of VRAM can cause stutters)

*   Enjoy Your Ryzentosh :)
