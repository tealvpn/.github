<p align="center">
  <img src="https://raw.githubusercontent.com/tealvpn/.github/main/profile/banner.png" alt="Teal VPN: private, fast, and built to connect on networks that block VPNs" width="100%">
</p>

<p align="center">
  <a href="https://github.com/tealvpn/android/releases/latest/download/TealVPN.apk"><img src="https://raw.githubusercontent.com/tealvpn/.github/main/profile/btn-android.png" alt="Download for Android" height="56"></a>
  <a href="https://github.com/tealvpn/windows/releases/latest/download/TealVPN-Setup-x64.exe"><img src="https://raw.githubusercontent.com/tealvpn/.github/main/profile/btn-windows.png" alt="Download for Windows" height="56"></a>
  <a href="https://github.com/tealvpn/mac/releases/latest/download/TealVPN.dmg"><img src="https://raw.githubusercontent.com/tealvpn/.github/main/profile/btn-mac.png" alt="Download for Mac" height="56"></a>
  <a href="https://github.com/tealvpn/linux/releases/latest/download/teal-vpn_amd64.deb"><img src="https://raw.githubusercontent.com/tealvpn/.github/main/profile/btn-linux.png" alt="Download for Linux" height="56"></a>
</p>
<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.tealvpn.client"><img src="https://raw.githubusercontent.com/tealvpn/.github/main/profile/btn-play.png" alt="Get it on Google Play" height="48"></a>
</p>
<p align="center">
  <sub>Also: <a href="https://github.com/tealvpn/windows/releases/latest/download/TealVPN-Setup-arm64.exe">Windows on ARM</a> · <a href="https://github.com/tealvpn/linux/releases/latest/download/teal-vpn_arm64.deb">Linux on ARM</a> · <a href="https://tealvpn.com/android-tv">Android TV</a> · <a href="https://tealvpn.com/chromebook">Chromebook</a> · <a href="https://tealvpn.com/ios">iPhone and iPad (soon)</a> · <a href="https://tealvpn.com">tealvpn.com</a></sub>
</p>

---

### Why Teal VPN

**Connects where others can't.** When a network blocks one way in, Teal quietly tries the next one, until it is through.

**No browsing logs.** Teal does not keep the sites you visit or the apps you use. Read the [privacy policy](https://tealvpn.com/privacy) and the [transparency page](https://tealvpn.com/transparency).

**Free every day.** A daily allowance with no card and no ads. Teal Pro opens every location with no data limit. [Get Teal VPN](https://tealvpn.com).

**One account, every device.** A [VPN for Android](https://tealvpn.com/android), [Windows](https://tealvpn.com/windows), [Mac](https://tealvpn.com/mac), [Linux](https://tealvpn.com/linux), [Android TV](https://tealvpn.com/android-tv) and [Chromebook](https://tealvpn.com/chromebook) ([iPhone](https://tealvpn.com/ios) soon), with [locations](https://tealvpn.com/locations) in Europe, North America and Asia.

### See it

<p align="center">
  <img src="https://raw.githubusercontent.com/tealvpn/android/main/screenshots/connect.webp" alt="Android: connected" width="220">
  <img src="https://raw.githubusercontent.com/tealvpn/android/main/screenshots/locations.webp" alt="Android: locations" width="220">
  <img src="https://raw.githubusercontent.com/tealvpn/android/main/screenshots/protection.webp" alt="Android: protection" width="220">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/tealvpn/windows/main/screenshots/connect.webp" alt="Windows: connected" width="680">
</p>

### Check that a download is genuine

Every release lists the SHA-256 of each file and carries a `.sha256` file next to it.

- **Android:** every direct APK is signed with our key. Signing certificate (SHA-256):
  ```
  75:68:15:FB:27:4D:04:A3:8E:E8:C9:BD:CA:A7:1D:0A:AE:65:F3:C6:B1:0D:5F:1C:43:BA:F7:D0:DC:8E:8C:24
  ```
  Check with `apksigner verify --print-certs TealVPN.apk`. An APK signed with any other key is not ours. Please don't install it.
- **Windows and Mac:** the system shows the publisher before the app opens; it must match the one named on [tealvpn.com](https://tealvpn.com).
- **Linux:** `sha256sum -c teal-vpn_amd64.deb.sha256`.

Download only from Google Play, [tealvpn.com](https://tealvpn.com) or this GitHub organization.

### What is here

| Repository | What it is |
|---|---|
| [android](https://github.com/tealvpn/android) | Signed Android releases (APK) for phones, tablets, Android TV and Chromebooks |
| [windows](https://github.com/tealvpn/windows) | Signed Windows installers, Intel / AMD and ARM |
| [mac](https://github.com/tealvpn/mac) | Signed and notarised Mac app (DMG) |
| [linux](https://github.com/tealvpn/linux) | Linux packages (.deb), Intel / AMD and ARM |
| [endpoints](https://github.com/tealvpn/endpoints) | A small signed file that helps the apps reach us when networks block them |

### Security

Found a security problem? Email **support@tealvpn.com** with the subject "Security". Please don't open a public issue for it.
