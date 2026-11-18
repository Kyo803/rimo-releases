# Rimo downloads

Windows installers for Rimo, a local-first desktop workbench.

**Source code is private. This repository publishes installers only.**

- [Download Rimo 0.13.0](https://github.com/Kyo803/rimo-releases/releases/tag/v0.13.0)
- [Latest installer](https://github.com/Kyo803/rimo-releases/releases/latest)
- Windows 10/11 x64
- Installers are unsigned; SmartScreen may ask for confirmation
- First launch opens the setup assistant and creates `~/Desktop/Rimo` or the folder you choose

## What is new in 0.13.0

E2EE cleanup: seal old plaintext messages from chat details, mark the safety code
verified with warnings when member devices change, encrypt attachment names and
MIME types, and encrypt the local decrypted cache at rest with Windows DPAPI.
Recovery codes and device revocation from 0.12.0 remain.

Per-message forward secrecy and full sender/timestamp metadata hiding are not
shipped; they need a protocol redesign. Old attachments/reactions are not
rewritten by sealing.

Also included since 0.6.0: first-run onboarding, sandboxed custom widgets, the
detective canvas, the GitHub tracker, ledger chat, profiles and profile
customization.

Rimo does not require an account, does not include telemetry and does not call
the network on launch. Chat and the GitHub tracker are opt-in; everything else
stays in your vault.
