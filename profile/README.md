<p align="center">
  <img src="https://raw.githubusercontent.com/tealvpn/.github/main/profile/logo.png" width="96" height="96" alt="Teal VPN">
</p>

<h1 align="center">Teal VPN</h1>

<p align="center">
  Fast, private VPN that keeps working on hard networks.<br>
  <a href="https://tealvpn.com">tealvpn.com</a> · <a href="mailto:support@tealvpn.com">support@tealvpn.com</a>
</p>

---

### Get Teal VPN

| Platform | Direct download (newest version) | Also from |
|---|---|---|
| Android phones and tablets | [TealVPN.apk](https://github.com/tealvpn/android/releases/latest/download/TealVPN.apk) | [Google Play](https://play.google.com/store/apps/details?id=com.tealvpn.client) · [tealvpn.com/android](https://tealvpn.com/android) |
| Android TV, Chromebook | [TealVPN.apk](https://github.com/tealvpn/android/releases/latest/download/TealVPN.apk) | [tealvpn.com/android-tv](https://tealvpn.com/android-tv) · [tealvpn.com/chromebook](https://tealvpn.com/chromebook) |
| Windows (Intel / AMD) | [TealVPN-Setup-x64.exe](https://github.com/tealvpn/windows/releases/latest/download/TealVPN-Setup-x64.exe) | [tealvpn.com/windows](https://tealvpn.com/windows) |
| Windows (ARM) | [TealVPN-Setup-arm64.exe](https://github.com/tealvpn/windows/releases/latest/download/TealVPN-Setup-arm64.exe) | [tealvpn.com/windows](https://tealvpn.com/windows) |
| Mac | [TealVPN.dmg](https://github.com/tealvpn/mac/releases/latest/download/TealVPN.dmg) | [tealvpn.com/mac](https://tealvpn.com/mac) |
| Linux (Ubuntu, Debian; Intel / AMD) | [teal-vpn_amd64.deb](https://github.com/tealvpn/linux/releases/latest/download/teal-vpn_amd64.deb) | [tealvpn.com/linux](https://tealvpn.com/linux) |
| Linux (ARM, Raspberry Pi) | [teal-vpn_arm64.deb](https://github.com/tealvpn/linux/releases/latest/download/teal-vpn_arm64.deb) | [tealvpn.com/linux](https://tealvpn.com/linux) |
| iPhone, iPad | | [tealvpn.com/ios](https://tealvpn.com/ios) |

Download only from Google Play, [tealvpn.com](https://tealvpn.com) or this GitHub organization.

### Check that a download is genuine

Every release lists the SHA-256 of each file and carries a `.sha256` file next to it.

- **Android:** every direct APK is signed by Teal VPN. Signing certificate (SHA-256):
  ```
  75:68:15:FB:27:4D:04:A3:8E:E8:C9:BD:CA:A7:1D:0A:AE:65:F3:C6:B1:0D:5F:1C:43:BA:F7:D0:DC:8E:8C:24
  ```
  Check with `apksigner verify --print-certs TealVPN.apk`. An APK signed with any other key is not ours. Please don't install it.
- **Windows and Mac:** Windows and macOS show the signer before the app opens; it must say the same publisher as on [tealvpn.com](https://tealvpn.com).
- **Linux:** compare the file with its `.sha256`: `sha256sum -c teal-vpn_amd64.deb.sha256`.

### What is here

| Repository | What it is |
|---|---|
| [android](https://github.com/tealvpn/android) | Signed Android releases (APK) |
| [windows](https://github.com/tealvpn/windows) | Signed Windows installers |
| [mac](https://github.com/tealvpn/mac) | Signed and notarised Mac app (DMG) |
| [linux](https://github.com/tealvpn/linux) | Linux packages (.deb) |
| [endpoints](https://github.com/tealvpn/endpoints) | A small signed file that helps the apps reach us when networks block them |

### Security

Found a security problem? Email **support@tealvpn.com** with the subject "Security". Please don't open a public issue for it.
