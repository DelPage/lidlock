# LidLock

Keep your Mac working, even with the lid closed.

[![macOS 13+](https://img.shields.io/badge/macOS-13%2B-111111?labelColor=0f172a)](https://support.apple.com/macos)
[![Signed and notarized](https://img.shields.io/badge/Developer%20ID-signed%20%2B%20notarized-22c55e?labelColor=0f172a)](https://developer.apple.com/developer-id/)
[![Download](https://img.shields.io/badge/Download-LidLock.dmg-2563eb?labelColor=0f172a)](https://github.com/DelPage/lidlock/releases/latest/download/LidLock.dmg)
[![Support LidLock](https://img.shields.io/badge/Support-LidLock-2FBC91?labelColor=0f172a)](SUPPORT.md)

LidLock helps keep your Mac awake for local servers, downloads, automations, and long builds.
What continues can depend on the app and macOS behavior. No Terminal commands required.

LidLock is free software published by DelPage Technologies.

<p align="center">
  <img src="assets/lidlock-icon.png" width="96" alt="LidLock app icon">
</p>

<p align="center">
  <img src="screenshots/lidlock-main.png" width="430" alt="LidLock showing four power modes and the Walk Away action">
</p>

## Free Download

- [Download LidLock.dmg](https://github.com/DelPage/lidlock/releases/latest/download/LidLock.dmg)
- Current version: **1.2.1**
- SHA-256: `3c760d3c33c738e73f24442422a9aed4bd8201aefdd6800afbf26bc24f642bc2`

LidLock requires **macOS 13 Ventura or newer**. Apple signs the distributed app
with Developer ID and notarizes it.

## Getting Started

Version 1.2.1 includes a short first launch guide to the sleep controls, Walk
Away, the menu bar, and administrator approval. You can reopen it anytime from
**Settings**, then **Getting Started**.

[Read the complete guide to install LidLock and review its permissions](GETTING_STARTED.md).

## What It Does

- **Normal Sleep** uses your Mac's normal sleep settings.
- **Stay Awake with Lid Closed** keeps the Mac awake after you close the lid. Your Lock Screen settings still apply.
- **Stay Awake** keeps your work running while the display can turn off.
- **Keep Screen On** keeps the Mac and display awake while the lid is open.
- **Walk Away** turns the display off without stopping your work.
- Closing the window keeps LidLock available in the menu bar; reopen it from
  **Open LidLock** or quit it explicitly from the same menu.
- In version 1.2.1, the lid-closed mode no longer issues a display sleep command
  when the lid closes. This removes LidLock's direct Lock Screen trigger. LidLock
  reads the lid-close setting back before showing **Active**, then holds a
  stronger system sleep assertion while active. macOS Lock Screen settings still
  apply.

## Permissions at a Glance

| Feature | Approval | Why |
|---|---|---|
| Normal Sleep, Stay Awake, Keep Screen On, and Walk Away | None | They work as soon as LidLock opens. |
| Stay Awake with Lid Closed | Administrator password | macOS protects changes to how the Mac sleeps with its lid shut. |
| Password-free lid control | Optional helper approval | A signed helper can change only the lid sleep setting. |
| Open at login | Optional Login Items approval | macOS lets you choose which apps open when you sign in. |

LidLock does not request access to files, screen contents, camera, microphone,
location, contacts, or Accessibility controls. Read
[Getting Started](GETTING_STARTED.md#permissions-and-approvals) for the full
explanation.

## Interface

| Sleep controls | First launch guide |
|---|---|
| ![LidLock four mode screen](screenshots/lidlock-main.png) | ![LidLock first launch guide](screenshots/lidlock-onboarding.png) |

## Privacy

LidLock is private by default:

- No accounts.
- No analytics.
- No telemetry.
- No automatic network access while you use LidLock.

Read the [LidLock privacy policy](PRIVACY.md).

## Support LidLock

LidLock is free and works the same for everyone. The
[Support LidLock page](SUPPORT.md) has $5, $10, $25, $100, and custom donation
options.

## Bug Reports

Use [GitHub Issues](https://github.com/DelPage/lidlock/issues) for bug reports and compatibility notes. Please include your macOS version, Mac model, LidLock version, and what you expected to happen.

## Closed Source Notice

This public repository contains releases, screenshots, and issue tracking. The
private source repository remains separate.

DelPage Technologies publishes LidLock as proprietary software. Read the
[EULA](EULA.md) for license terms and [CONTRIBUTING](CONTRIBUTING.md) for the
public repository boundary.

## Links

- Releases: [GitHub Releases](https://github.com/DelPage/lidlock/releases)
- Getting started: [GETTING_STARTED.md](GETTING_STARTED.md)
- Privacy policy: [PRIVACY.md](PRIVACY.md)
- Support: [SUPPORT.md](SUPPORT.md)
- Changelog: [CHANGELOG.md](CHANGELOG.md)
