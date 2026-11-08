# REMOREMO Host for macOS

REMOREMO Host lets you connect to your Mac using REMOREMO Client on iPhone or iPad.

## Download

- [Download REMOREMO Host for Apple Silicon](https://github.com/moflutter/remoremo-host/releases/latest/download/REMOREMO-Host-macos-arm64.dmg)
- [Latest release and installation notes](https://github.com/moflutter/remoremo-host/releases/latest)
- [SHA-256 checksums](https://github.com/moflutter/remoremo-host/releases/latest/download/SHA256SUMS)

## Requirements

- Apple Silicon Mac (arm64)
- macOS 13.0 or later
- REMOREMO Client
- For initial pairing, the Mac and Client device must be on the same LAN and able to communicate with each other.

## Installation

1. Download and open the DMG.
2. Drag **REMOREMO Host.app** to **Applications**.
3. Launch REMOREMO Host from Applications.
4. Grant the required macOS permissions. Screen Recording and Accessibility permissions may be required for remote control.
5. Select **Show QR Code** from the Host menu in the menu bar.
6. Scan the QR code with REMOREMO Client and approve pairing on the Mac. Allow local network access on the Client when prompted.

The release DMG is signed with Developer ID, notarized by Apple, and stapled. You do not need to disable Gatekeeper.

## Verify a download

Download the DMG and `SHA256SUMS` from the same release into the same folder, then run:

```sh
shasum -a 256 -c SHA256SUMS
```

This repository contains distribution information and release binaries only. It does not contain the application's development source code. Intel Macs are not supported by this release.

## Legal information

- [Terms of Service](https://moflutter.github.io/remoremo-legal/terms/)
- [Privacy Policy](https://moflutter.github.io/remoremo-legal/privacy/)

The web policy describes v6 signaling and device storage. Installed app versions may contain an earlier bundled document.
