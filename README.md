# Rimo downloads

Windows installers for Rimo, a local-first desktop workbench.

**Source code is private. This repository publishes installers only.**

- [Download Rimo 0.7.0](https://github.com/Kyo803/rimo-releases/releases/tag/v0.7.0)
- [Latest installer](https://github.com/Kyo803/rimo-releases/releases/latest)
- Windows 10/11 x64
- Installers are unsigned; SmartScreen may ask for confirmation
- First launch opens the setup assistant and creates `~/Desktop/Rimo` or the folder you choose

## What is new in 0.7.0

Accounts and chat: create a Rimo account or sign in from the Chat tab, search
people by name or @username, start direct or group conversations and message
from the desktop app. Unread badges, read state, sender avatars and day
separators are included. The session token lives in the Rust vault and never
reaches the webview; passwords go straight to the account server over HTTPS.

Chat is stored in PostgreSQL on the Rimo account server, not faked locally.
The API runs at `rimo-api.xochat.online` and `rimo-chat.xochat.online` behind a
dedicated Rimo Cloudflare tunnel. Signing out and back in keeps your history.

Also included since 0.6.0: first-run onboarding, sandboxed custom widgets, the
detective canvas, the GitHub tracker and a local SQLite vault.

Rimo does not require an account, does not include telemetry and does not call
the network on launch. Chat and the GitHub tracker are opt-in; everything else
stays in your vault. Accounts currently use email/username + password; Google
sign-in, attachments, reactions and typing/presence come later.
