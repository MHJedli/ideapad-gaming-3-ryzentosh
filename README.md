# Ryzentosh EFI for Lenovo Ideapad gaming 3 (15ACH6)
![Screenshot 2024-03-04 at 11 15 59 PM](https://github.com/Mouadh-Jedli/ideapad-gaming-3-ryzentosh/assets/53920740/b4e5eba3-fc70-442b-9db0-631a83ccb743)

<div id="badges" align="center">
  <img src="https://img.shields.io/badge/OC-1.0.0-blue">
  <img src="https://img.shields.io/badge/macOS-Ventura_13.6.6-orange">
  <img src="https://img.shields.io/badge/macOS-Sonoma_14.1.1-green">
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
| SMBIOS used  | iMac Pro (Regenerate the SMBIOS with the **same macbook model**)  |
| MacOS Version  | MacOS Ventura 13.6.6 + Sonoma 14.1.1  |

# What's Working

| Item | Status | Notes |
| --- | --- | --- |
| CPU | ✅ |   |
| IGPU | ✅ | NootedRed.kext |
| Brightness Control | ✅ | Lunar App |
| HDMI A/V out | ✅ |   |
| USB | ✅ |  |
| Keyboard | ✅ | VoodooPS2Controller.kext |
| Audio | ✅ | AppleALC kext working with layout-id 11 |
| Trackpad | ✅ | VoodooI2C.kext |
| Ethernet | ✅ | RealtekRTL8111.kext |
| AppleTV+ DRM | ✅ |  |
| Shutdown/Reboot | ✅ |   |
| iServices | ✅ | FaceTime + Messages  |
| Microphone | ✅ | Recently fixed after AppleALC update |

# What's not Working

| Item | Status | Notes |
| --- | --- | --- |
| Sleep | ❓ |  |
| DGPU | ❌ | RTX 3000 series were never supported |
| Wi-Fi | ❌ | RTL8522AE not supported (Using dongle instead) |
| Bluetooth | ❌ |  |
| AirDrop | ❌ |  |

# Bios Options

*   Secure Boot : **Disabled**
*   Boot Type : **UEFI**

# Screenshots

![Screenshot 2024-03-04 at 9 53 52 PM](https://github.com/Mouadh-Jedli/ideapad-gaming-3-ryzentosh/assets/53920740/e462de51-04b2-465e-aabc-f7e8b0e86be2)
<br>
![Screenshot 2024-03-04 at 9 54 56 PM](https://github.com/Mouadh-Jedli/ideapad-gaming-3-ryzentosh/assets/53920740/b6f84347-185f-4c2c-971d-03408263283d)
<br>
![Screenshot 2024-03-04 at 9 56 02 PM](https://github.com/Mouadh-Jedli/ideapad-gaming-3-ryzentosh/assets/53920740/497a6a2c-ac15-48f6-9c81-409d0541b8aa)


# VERY IMPORTANT !

*   **DON'T** update these kext because it **WILL** lead to unfunctional TrackPad :
  <br>- VoodooI2C.kext
  <br>- VoodooI2CHID.kext
  <br>- VoodooPS2Controller.kext

*   Sometimes the keyboard doesn't work from boot to boot, so a reboot is required from time to time.<br>
    When booting, press some keys. ( I feel it helps :> )

*   Sometimes the System won't boot so you need to reboot multiple times if needed. A solution ,I think, is<br>
    to plug in a mouse. ( tbh I have no clue why and it is what it is )

*   When doing a minor update (or a major one if you choose to ) :
    <br>1- Remove NootedRed.kext temporarily
    <br>2- Update your System
    <br>3- After the system booted after your update, Restore NootedRed.kext to its place

*   Increase your VRAM size for better and smooth experience (512 MB of VRAM can cause stutters)

*   Enjoy Your Ryzentosh :)
