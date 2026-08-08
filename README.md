# Ryzentosh EFI for Lenovo Ideapad gaming 3 (15ACH6)
<img width="1920" height="1080" alt="Screenshot 2026-06-14 at 10 08 05 AM" src="https://github.com/user-attachments/assets/3edc0133-5de5-4941-a666-219718c208ca" />

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
| HDMI | ✅ | Wired to IGPU |
| Brightness Control | ✅ | Native Keys (F5/F6) |
| USB | ✅ | Using USBInjectAll.kext |
| Keyboard | ✅ | VoodooPS2Controller.kext |
| Audio + Mic | ✅ | Fixed using [MyKextInstaller](https://github.com/Mirone/MyKextInstaller) or [OCLP-MOD](https://github.com/laobamac/OCLP-Mod) |
| Trackpad | ✅ | VoodooI2C.kext |
| Ethernet | ✅ | RealtekRTL8111.kext [**v2.4.2**](https://github.com/Mieze/RTL8111_driver_for_OS_X/issues/90) |
| USB WIFI Dongle | ✅ | Supported TL-WN Model From [chris1111 Tahoe guide](https://github.com/chris1111/Wireless-USB-Big-Sur-Adapter/blob/master/Usage-macOS-Tahoe.md) |
| Shutdown/Reboot | ✅ |   |


# What's not Working

| Item | Status | Notes |
| --- | --- | --- |
| Sleep | ❓ | |
| DGPU | ❌ | RTX 3050Ti is NOT supported |
| Built-In Wi-Fi + Bluetooth | ❌ | RTL8522AE not supported |
| AirDrop | ❌ |  |
| Phone Detection | ❌ | When Applying the root patches |

>[!important]
>Be aware that when applying the root patches, MacOS will **NOT** be able to detect your phones devices (Android/iOS)<br>
>**You have been warned !**

# Bios Options

*   Secure Boot : **Disabled**
*   Boot Type : **UEFI**


# VERY IMPORTANT !

*   Before upgrading to macOS Tahoe, don't forget to sign out of ICloud because of the change of macbook model

*   Remove the `-v` from `boot-args` to boot without Verbose Mode

*   Increase your VRAM size for better and smooth experience (512 MB of VRAM can cause stutters)

*   Enjoy Your Ryzentosh :)
