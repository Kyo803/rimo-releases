# Rimo downloads

Windows installers for Rimo, a local-first desktop workbench.

**Source code is private. This repository publishes installers only.**

- [Download Rimo 0.12.0](https://github.com/Kyo803/rimo-releases/releases/tag/v0.12.0)
- [Latest installer](https://github.com/Kyo803/rimo-releases/releases/latest)
- Windows 10/11 x64
- Installers are unsigned; SmartScreen may ask for confirmation
- First launch opens the setup assistant and creates `~/Desktop/Rimo` or the folder you choose

## What is new in 0.12.0

E2EE recovery and device management: generate a one-time recovery code, restore
the device key and chat history on a new machine, and revoke other devices from
the profile editor. Revoking removes the device's sessions and wrapped keys and
rotates conversations opened on the current device.

Chat remains end-to-end encrypted; profile customization, ledger messaging,
media, groups, search, typing, presence and read receipts remain from earlier
releases.

Still later: per-message forward secrecy, retroactive encryption, metadata
privacy, cache encryption at rest, OS notifications, offline send queue, voice
notes, calls, email verification/reset, imported animated profile assets and
friend/message requests.

Also included since 0.6.0: first-run onboarding, sandboxed custom widgets, the
detective canvas, the GitHub tracker, profiles and a local SQLite vault.

Rimo does not require an account, does not include telemetry and does not call
the network on launch. Chat and the GitHub tracker are opt-in; everything else
stays in your vault.
