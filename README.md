# Rimo downloads

Windows installers for Rimo, a local-first desktop workbench.

**Source code is private. This repository publishes installers only.**

- [Download Rimo 0.4.0](https://github.com/Kyo803/rimo-releases/releases/tag/v0.4.0)
- [Latest installer](https://github.com/Kyo803/rimo-releases/releases/latest)
- Windows 10/11 x64
- Installers are unsigned; SmartScreen may ask for confirmation
- First launch creates `~/Desktop/Rimo`

## What is new in 0.4.0

Custom widgets: add **Widget -> Custom code** on the dashboard and write HTML,
CSS and JS with a live preview. Rimo injects its theme and a small read-only API.
Widgets are sandboxed with no same-origin, no Tauri access and no network.

Also included: the canvas reader, task checkboxes, device image import and
optional image sharing from 0.3.0, plus GitHub stack analysis, syntax colours,
calendars and the local vault.

Rimo does not require an account, does not include telemetry and does not call
the network on launch. Optional online features are opt-in.
