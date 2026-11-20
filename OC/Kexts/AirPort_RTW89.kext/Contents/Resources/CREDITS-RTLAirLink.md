# Credits and provenance

RTLAirLink is a renamed distribution of the experimental Owly development work derived from [FranciumOS AirPort_RTW89](https://github.com/FranciumOS-org/AirPort_RTW89). It is not a claim of sole authorship of the inherited Wi-Fi driver. Original source notices remain in place.

- **Realtek and Linux wireless developers**: Linux rtw89 and Linux networking headers. The vendored driver includes local AWDL/filter integration changes; see source and MODIFICATIONS.md.
- **AirPort_RTW89, AirPort_RTW88 and Realtek-AirPort-Family contributors**: macOS port foundations, compatibility shims and Wi-Fi glue.
- **Owly development work**: the guarded native AWDL frontend/backend integration, radio-peer handling and Lilu event/client bridge.
- **OpenIntelWireless**: references for third-party IO80211 integration.
- **Acidanthera**: Lilu, MacKernelSDK and OpenCore; preserve the individual vendor notices in their source snapshots.
- **OpenCore Legacy Patcher contributors**: references for the Legacy Wi-Fi dependency arrangement. Apple system kexts are not redistributed here.
- **hostap/wpa_supplicant and Mbed TLS contributors**: WPA3-related code under their respective licenses.
- **Realtek/linux-firmware**: unchanged firmware blobs under LICENCE.rtlwifi_firmware.txt.

The pre-existing resource credits are retained at Resources/CREDITS.md and inside the main kext. GPL text is at LICENSE; third-party notices are also collected under LICENSES. RTLAirLink packaging/build changes are dated in MODIFICATIONS.md.
