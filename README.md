# Rimo downloads

Windows installers for Rimo, a local-first desktop workbench.

**Source code is private. This repository publishes installers only.**

- [Download Rimo 0.9.0](https://github.com/Kyo803/rimo-releases/releases/tag/v0.9.0)
- [Latest installer](https://github.com/Kyo803/rimo-releases/releases/latest)
- Windows 10/11 x64
- Installers are unsigned; SmartScreen may ask for confirmation
- First launch opens the setup assistant and creates `~/Desktop/Rimo` or the folder you choose

## What is new in 0.9.0

Chat is end-to-end encrypted. Each desktop has an X25519 device key, each
conversation has a random 256-bit key wrapped for member devices, and message
bodies, reactions and attachments reach the server as AES-256-GCM ciphertext.
The server stores wrapped keys and ciphertext only.

Search now runs locally over a decrypted cache instead of on the server, and
chat details shows a safety code derived from every member device fingerprint.
The ledger message design, replies, edits, attachments, groups, pin/mute,
blocking, profiles and account controls from 0.8.0 remain.

Metadata such as membership, sender, timestamps and file names is still visible
to the server. There is no per-message ratchet yet, no portable key backup and no
device-management UI; messages sent before 0.9.0 remain in the old plaintext
format.

Also included since 0.6.0: first-run onboarding, sandboxed custom widgets, the
detective canvas, the GitHub tracker and a local SQLite vault.

Rimo does not require an account, does not include telemetry and does not call
the network on launch. Chat and the GitHub tracker are opt-in; everything else
stays in your vault.
