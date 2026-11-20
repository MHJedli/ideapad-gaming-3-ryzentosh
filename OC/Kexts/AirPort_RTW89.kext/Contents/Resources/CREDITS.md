# Credits

AirPort_RTW89 stands on the work of these projects and their contributors.

- **Linux rtw89** (Realtek and the Linux wireless developers): the driver for
  the chip itself, vendored in `third_party/rtw89/` (unmodified apart from
  RTLAirLink's AWDL changes, below), and the 802.11 headers in
  `third_party/linux-include/`. Parts of Linux's mac80211 and
  cfg80211 were followed closely in `src/compat_rtw89/`.
- **AirPort_RTW88** and **Realtek-AirPort-Family**: the Linux-API shims in
  `src/compat/`, the kext glue this port started from, MacKernelSDK, and the
  reference for macOS's newer Wi-Fi request formats.
- **OpenIntelWireless** (itlwm, AirportItlwm): how a third-party driver works
  with Apple's IO80211 family.
- **OpenCore Legacy Patcher** and **Acidanthera**: the old Wi-Fi stack
  (`IOSkywalkFamily`, `IO80211FamilyLegacy`) as a loadable set, and AMFIPass;
  OpenCore and Lilu.
- **hostap** (wpa_supplicant/hostapd) and **Mbed TLS**: vendored for WPA3.
- **Realtek**: the chip's firmware, from linux-firmware.
- **RTLAirLink** (Anh Tài, [taingo936-ui/RTLAirLink](https://github.com/taingo936-ui/RTLAirLink),
  GPL-2.0), the Owly development work: the AWDL that makes AirDrop work, built
  on AirPort_RTW89 0.5.0 and merged back from its v0.1.0 -- the `owly_*` files
  in `src/`, its changes to the glue, MLME, front and driver, the changes to
  `third_party/rtw89/` it needs (cam, chan, core, fw, mac, mac80211, phy, ser),
  and the Lilu event bridge in `bridge/` (with Lilu's headers, BSD-3-Clause).
  Its own credits and change log: `CREDITS-RTLAirLink.md`,
  `MODIFICATIONS-RTLAirLink.md`.
