# Rimo downloads

Windows installers for Rimo, a local-first desktop workbench.

**Source code is private. This repository publishes installers only.**

- [Download Rimo 0.8.0](https://github.com/Kyo803/rimo-releases/releases/tag/v0.8.0)
- [Latest installer](https://github.com/Kyo803/rimo-releases/releases/latest)
- Windows 10/11 x64
- Installers are unsigned; SmartScreen may ask for confirmation
- First launch opens the setup assistant and creates `~/Desktop/Rimo` or the folder you choose

## What is new in 0.8.0

Chat is rebuilt as a ledger, not a bubble stream. Sender stamps and times sit in
the margin, message bodies read like manuscript lines, reactions are pressed as
small seals, photos arrive as paper plates, replies are quoted strips, and new
messages are marked with a folio line.

Everything around it is real too: direct and group conversations, replies,
edits, deletes, mentions, markdown-lite, emoji, images/GIFs/video/audio/files
up to 10 MB, typing indicators, presence, read receipts, search, pin/mute,
member management, blocking, profiles, password change and account deletion.
Attachments download only for conversation members; the session token stays in
the Rust vault and never enters the webview.

Still later: voice/video calls, end-to-end encryption, email verification,
password reset, offline message cache and OS-level notifications.

Also included since 0.6.0: first-run onboarding, sandboxed custom widgets, the
detective canvas, the GitHub tracker and a local SQLite vault.

Rimo does not require an account, does not include telemetry and does not call
the network on launch. Chat and the GitHub tracker are opt-in; everything else
stays in your vault.
