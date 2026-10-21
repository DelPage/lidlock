# LidLock

Keep your Mac working, even with the lid closed.

[![macOS 13+](https://img.shields.io/badge/macOS-13%2B-111111?labelColor=0f172a)](https://support.apple.com/macos)
[![Signed and notarized](https://img.shields.io/badge/Developer%20ID-signed%20%2B%20notarized-22c55e?labelColor=0f172a)](https://developer.apple.com/developer-id/)
[![Download](https://img.shields.io/badge/Download-LidLock.dmg-2563eb?labelColor=0f172a)](https://github.com/DelPage/lidlock/releases/latest/download/LidLock.dmg)
[![Support LidLock](https://img.shields.io/badge/Support-LidLock-2FBC91?labelColor=0f172a)](SUPPORT.md)

LidLock keeps your Mac awake for downloads, local servers, automations, and long
builds. Whether work continues depends on the app and macOS. It is free to use
and requires no Terminal commands.

Published by DelPage Technologies.

<p align="center">
  <img src="assets/lidlock-icon.png" width="96" alt="LidLock app icon">
</p>

<p align="center">
  <img src="screenshots/lidlock-main.png" width="430" alt="LidLock showing four power modes and the Walk Away action">
</p>

## Free Download

- [Download LidLock.dmg](https://github.com/DelPage/lidlock/releases/latest/download/LidLock.dmg)
- Current version: **1.2.3**
- SHA-256: `3b39eab9250b8778759ed48663db7372bb9607d17a45f971f92f60066015c2b8`

LidLock requires **macOS 13 Ventura or newer**. DelPage signs the app with
Apple Developer ID, and Apple notarizes it.

## Getting Started

LidLock tells you before macOS needs an administrator password or approval in
Login Items. Reopen the setup guide from **Settings**, then **Getting Started**.

[Read the installation and permissions guide](GETTING_STARTED.md).

## What It Does

- **Normal Sleep** uses your Mac's normal sleep settings.
- **Stay Awake with Lid Closed** keeps work running with the lid closed. The MacBook display turns off; your Lock Screen settings still apply.
- **Stay Awake (Lid Open)** keeps work running with the lid open. The display follows your Mac’s sleep timer.
- **Keep Screen On (Lid Open)** keeps the display on with the lid open. Closing the lid can put your Mac to sleep.
- **Walk Away** turns the display off without stopping your work.
- Closing the window leaves LidLock in the menu bar. Use **Open LidLock** to
  reopen it or **Quit LidLock** to exit.

## Display Off Without Locking

Choose **Stay Awake with Lid Closed** to keep work running with the MacBook
display off. Keeping the Mac awake does not prevent it from locking.

Open **Display Off Without Locking…** from LidLock’s main window, menu bar, or
Settings. The guide opens macOS **Lock Screen** settings, where you can set
**Require password after screen saver begins or display is turned off** to
**Never**. This also stops automatic locking after display sleep outside
LidLock. LidLock does not change this preference itself or unlock a locked Mac.

See [Apple’s Lock Screen settings guide](https://support.apple.com/guide/mac-help/change-lock-screen-settings-on-mac-mh11784/mac).

## Permissions

| Feature | Approval | Why |
|---|---|---|
| Normal Sleep, Stay Awake, Keep Screen On, and Walk Away | None | Available as soon as LidLock opens. |
| Stay Awake with Lid Closed | Administrator password unless **Allow lid changes without a password** is enabled | macOS protects changes to lid sleep behavior. |
| Allow lid changes without a password | Login Items approval may be required | Avoids password prompts for lid changes. |
| Open at login | Login Items approval may be required | Lets LidLock open when you sign in. |

When approval is needed, LidLock explains why and can open Login Items.

LidLock does not request access to files, screen contents, camera, microphone,
location, contacts, or Accessibility controls. Read
[Getting Started](GETTING_STARTED.md#permissions-and-approvals) for details.

## Interface

| Sleep controls | First launch guide |
|---|---|
| ![LidLock four mode screen](screenshots/lidlock-main.png) | ![LidLock first launch guide](screenshots/lidlock-onboarding.png) |

## Privacy

LidLock has no accounts, analytics, telemetry, advertising, or automatic
network access while it runs.

Read the [LidLock privacy policy](PRIVACY.md).

## Support LidLock

LidLock works the same whether or not you donate. Optional donations support
continued maintenance. Visit [Support LidLock](SUPPORT.md) to contribute.

## Bug Reports

Use [GitHub Issues](https://github.com/DelPage/lidlock/issues) for bug reports
and compatibility notes. Include your macOS version, Mac model, LidLock
version, and what you expected to happen.

## Repository

This repository contains LidLock downloads, documentation, screenshots, and
issue tracking. The app's source code is not public. See the [EULA](EULA.md)
for license terms and [CONTRIBUTING](CONTRIBUTING.md) for what belongs here.

## Links

- Releases: [GitHub Releases](https://github.com/DelPage/lidlock/releases)
- Getting started: [GETTING_STARTED.md](GETTING_STARTED.md)
- Privacy policy: [PRIVACY.md](PRIVACY.md)
- Support: [SUPPORT.md](SUPPORT.md)
- Changelog: [CHANGELOG.md](CHANGELOG.md)
