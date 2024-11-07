# Ryzentosh EFI for Lenovo Ideapad gaming 3 (15ACH6)
![Screenshot 2024-11-04 at 10 45 41 AM](https://github.com/user-attachments/assets/fc4650e1-cd23-4370-b0b3-c243daa4199d)

<div id="badges" align="center">
  <img src="https://img.shields.io/badge/OC-1.0.2-blue">
  <img src="https://img.shields.io/badge/macOS-Ventura_13.7-orange">
  <img src="https://img.shields.io/badge/macOS-Sonoma_14.7.1-green">
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
| SMBIOS used  | MacBookPro 16,3 (Regenerate the SMBIOS with the **same macbook model**)  |

# What's Working

| Item | Status | Notes |
| --- | --- | --- |
| CPU | ✅ | AMD Ryzen 5 5600H |
| IGPU | ✅ | NootedRed.kext |
| Brightness Control | ✅ | Native Keys (F5/F6) |
| HDMI A/V out | ✅ | HDMI Port Wired to IGPU |
| USB | ✅ | USB Remapped with USBMap |
| Keyboard | ✅ | VoodooPS2Controller.kext |
| Audio | ✅ | AppleALC with layout-id=11 |
| Trackpad | ✅ | VoodooI2C.kext |
| Ethernet | ✅ | RealtekRTL8111.kext |
| AppleTV+ DRM | ✅ |  |
| Shutdown/Reboot | ✅ |   |
| iServices | ✅ |  |
| Microphone | ✅ | Recently fixed after AppleALC update |

# What's not Working

| Item | Status | Notes |
| --- | --- | --- |
| Sleep | ❓ |  |
| DGPU | ❌ | RTX 3050Ti is NOT supported |
| Wi-Fi | ❌ | RTL8522AE not supported |
| Bluetooth | ❌ |  |
| AirDrop | ❌ |  |

# Bios Options

*   Secure Boot : **Disabled**
*   Boot Type : **UEFI**

# Screenshots
*  Flutter Development with IOS Simulator

![Screenshot 2024-11-04 at 10 47 46 AM](https://github.com/user-attachments/assets/34cb5e51-a67d-4775-9153-356339491347)

<br>

![Screenshot 2024-11-04 at 10 48 01 AM](https://github.com/user-attachments/assets/c2bb0256-249f-4bbd-be2e-187d13993842)

<br>
*  Install Oracle <b>VirtualBox 6.1</b> to be able to use VMs

![Screenshot 2024-11-04 at 10 48 41 AM](https://github.com/user-attachments/assets/0b13e2b9-de1b-4e90-90f7-bb231c9b8f9b)

# VERY IMPORTANT !

*   Verbose Mode Disabled by Default

*   Increase your VRAM size for better and smooth experience (512 MB of VRAM can cause stutters)

*   Enjoy Your Ryzentosh :)
