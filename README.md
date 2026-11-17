# Rimo downloads

Windows installers for Rimo, a local-first desktop workbench.

**Source code is private. This repository publishes installers only.**

- [Download Rimo 0.10.0](https://github.com/Kyo803/rimo-releases/releases/tag/v0.10.0)
- [Latest installer](https://github.com/Kyo803/rimo-releases/releases/latest)
- Windows 10/11 x64
- Installers are unsigned; SmartScreen may ask for confirmation
- First launch opens the setup assistant and creates `~/Desktop/Rimo` or the folder you choose

## What is new in 0.10.0

Proper profiles on top of end-to-end encrypted chat: upload an avatar and banner,
set pronouns, a status line and a bio, and open a real profile card from any
avatar or name. Avatar images replace initials across the ledger, conversation
list, headers and member lists. Presence can be hidden.

Profile images are public to signed-in accounts. Chat message bodies, reactions
and attachments remain AES-256-GCM encrypted; the server stores ciphertext and
wrapped conversation keys only.

Frames, nameplates, custom profile effects, voice/video calls, per-message
forward secrecy, portable key backup and email recovery are later work.

Also included since 0.6.0: first-run onboarding, sandboxed custom widgets, the
detective canvas, the GitHub tracker, the ledger chat design and a local SQLite
vault.

Rimo does not require an account, does not include telemetry and does not call
the network on launch. Chat and the GitHub tracker are opt-in; everything else
stays in your vault.
