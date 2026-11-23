# BiOS — Releases

Official public releases and installer downloads of BiOS desktop apps.

| App | Latest | Download |
| --- | --- | --- |
| BIOS Desktop Widget | 2.3.0 | [BIOS-Widget-Setup.exe](https://github.com/LeoPalanca/bios-releases/releases/latest/download/BIOS-Widget-Setup.exe) (~2.5 MB) |
| BoardAssistant Studio | 1.2.0 | [BoardAssistant-Studio-Setup.exe](https://github.com/LeoPalanca/bios-releases/releases/download/boardassistant-studio-v1.2.0/BoardAssistant-Studio-Setup.exe) (~115 MB) |

Each app's current version, download address and SHA-256 are in `apps/<app>.json`.

## BIOS Desktop Widget

### Installation:
1. Download BIOS-Widget-Setup.exe.
2. Double-click to install.
3. No administrator privileges or IT permissions required (installs per-user to %LOCALAPPDATA%\Programs\BIOS Widget).
4. Launches automatically and creates Start Menu and optional Startup shortcuts.

## BoardAssistant Studio

The desktop app for building Board applications with BoardAutomate: project tabs, 16:9 screen previews, the client's design system, a read-only Board inventory and an assistant (DeepSeek or Claude through Pi, or Claude Code with your own sign-in).

### Installation:
1. Download BoardAssistant-Studio-Setup.exe and double-click it. It installs per-user, no administrator rights needed.
2. The installer is not code-signed: the first time, Windows SmartScreen asks for confirmation (More info, then Run anyway).
3. Requirements: Windows 10 or 11, Node.js 22 or later, and a BoardAutomate folder (Studio asks for it on first start).
4. From 1.1.0 Studio updates itself: a newer version appears above the model selector. Version 1.0.0 has to be replaced by hand once.
