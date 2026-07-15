# LidLock

Keep your Mac working, even with the lid closed.

[![macOS 13+](https://img.shields.io/badge/macOS-13%2B-111111?labelColor=0f172a)](https://support.apple.com/macos)
[![Signed and notarized](https://img.shields.io/badge/Developer%20ID-signed%20%2B%20notarized-22c55e?labelColor=0f172a)](https://developer.apple.com/developer-id/)
[![Download](https://img.shields.io/badge/Download-LidLock.dmg-2563eb?labelColor=0f172a)](https://github.com/DelPage/lidlock/releases/latest/download/LidLock.dmg)
[![Support LidLock](https://img.shields.io/badge/Support-LidLock-2FBC91?labelColor=0f172a)](SUPPORT.md)

LidLock keeps Claude Code, Codex, local servers, downloads, automations, and long builds running
when your Mac would normally sleep. No Terminal commands required.

LidLock is free software published by DelPage Technologies.

<p align="center">
  <img src="assets/lidlock-icon.png" width="96" alt="LidLock app icon">
</p>

<p align="center">
  <img src="screenshots/lidlock-main.png" width="430" alt="LidLock preview showing four power modes and the Walk Away action">
</p>

<p align="center">
  <em>Preview of the next signed LidLock update, currently being tested.</em>
</p>

## Free Download

- [Download LidLock.dmg](https://github.com/DelPage/lidlock/releases/latest/download/LidLock.dmg)
- Current version: **1.1.3**
- SHA-256: `fe735f2a9cebdbd5807163d4099c75df6141d70ca36aa91265562caf1d78e8af`

LidLock requires **macOS 13 Ventura or newer**. The distributed app is signed with Apple Developer ID and notarized by Apple.

## Getting Started

The next signed update includes a short first-run guide to the sleep controls,
Walk Away, the menu bar, and administrator approval. You can reopen it anytime
from **Settings**, then **Getting Started**.

[Read the complete installation and permissions guide](GETTING_STARTED.md).

## What It Does

- **Normal Sleep** uses your Mac's normal sleep settings.
- **Lid Closed** keeps your MacBook working with the lid shut while displays turn off.
- **Stay Awake** keeps your work running while the display can turn off.
- **Keep Screen On** keeps the Mac and display awake.
- **Walk Away** turns the display off immediately without stopping your work.
- Closing the window keeps LidLock available in the menu bar; reopen it from
  **Open LidLock** or quit it explicitly from the same menu.

## Permissions at a Glance

| Feature | Approval | Why |
|---|---|---|
| Normal Sleep, Stay Awake, Keep Screen On, and Walk Away | None | They work as soon as LidLock opens. |
| Lid Closed | Administrator password | macOS protects changes to how the Mac sleeps with its lid shut. |
| Password-free lid control | Optional helper approval | A signed helper can change only the lid sleep setting. |
| Open at login | Optional Login Items approval | macOS lets you choose which apps open when you sign in. |

LidLock does not request access to files, screen contents, camera, microphone,
location, contacts, or Accessibility controls. Read
[Getting Started](GETTING_STARTED.md#permissions-and-approvals) for the full
explanation.

## Next Update Preview

These screenshots are from the next signed update. The download above remains
version 1.1.3 until that update is published.

| Sleep controls | First-run guide |
|---|---|
| ![LidLock four-mode screen](screenshots/lidlock-main.png) | ![LidLock first-run guide](screenshots/lidlock-onboarding.png) |

## Privacy

LidLock is private by default:

- No accounts.
- No analytics.
- No telemetry.
- No automatic network access during normal operation.

Read the [LidLock privacy policy](PRIVACY.md).

## Support LidLock

LidLock is free and works the same for everyone. The
[Support LidLock page](SUPPORT.md) has $5, $10, $25, $100, and custom donation
options.

## Bug Reports

Use [GitHub Issues](https://github.com/DelPage/lidlock/issues) for bug reports and compatibility notes. Please include your macOS version, Mac model, LidLock version, and what you expected to happen.

## Closed Source Notice

This public repository is for distribution, screenshots, releases, and issue tracking. The LidLock application source code is not published here.

LidLock is proprietary software from DelPage Technologies. See [EULA.md](EULA.md)
for the license terms that apply to the compiled app and [CONTRIBUTING.md](CONTRIBUTING.md)
for the public-repository boundary.

## Links

- Releases: [GitHub Releases](https://github.com/DelPage/lidlock/releases)
- Getting started: [GETTING_STARTED.md](GETTING_STARTED.md)
- Privacy policy: [PRIVACY.md](PRIVACY.md)
- Support: [SUPPORT.md](SUPPORT.md)
- Changelog: [CHANGELOG.md](CHANGELOG.md)