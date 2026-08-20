# Changelog

This changelog records current and retired LidLock releases. Downloads are
available only for versions shown in GitHub Releases.

## 1.2.2 - 2026-08-20

- Added clear explanations before macOS asks for an administrator password.
- Added shortcuts to Login Items when macOS needs approval.
- Settings now shows pending approvals.
- If normal sleep cannot be restored, LidLock stays open and explains the
  available choices before quitting.
- Updated first launch and Settings guidance to show which controls need
  approval.

Artifact:

- `LidLock.dmg`
- SHA-256: `7972ce8f12760ec576b0d72eff97d0731057e9de36c317dca45cde12a86a3d1a`

## 1.2.1 - 2026-08-20

- Renamed the mode to **Stay Awake with Lid Closed**.
- The mode no longer forces the Lock Screen. Your macOS Lock Screen settings
  continue to apply.
- Improved reliability when starting and maintaining the mode.

Artifact:

- `LidLock.dmg`
- SHA-256: `3c760d3c33c738e73f24442422a9aed4bd8201aefdd6800afbf26bc24f642bc2`

## 1.2.0 - 2026-08-20

- Replaced separate power switches with four sleep modes.
- Added **Keep Running with Lid Closed** so work can continue after the lid
  closes while the displays are off. This mode was renamed **Stay Awake with
  Lid Closed** in version 1.2.1.
- Added a first launch guide for the modes, Walk Away, menu bar access, and
  approvals.
- Added Walk Away as a separate action that turns off the display without
  stopping work.
- Added the Support LidLock page and donation choices.
- Signed and notarized both the app and disk image.

Artifact:

- `LidLock.dmg`
- SHA-256: `56fcf464a2937557661f1b2c49d8f8d1ec465ac9dee36a9415e239a7c37e8a95`

## 1.1.3 - 2026-07-15

- Closing the main window now leaves LidLock in the macOS menu bar.
- Hovering over the menu bar icon shows the current sleep setting.
- **Open LidLock** brings the window back.
- **Quit LidLock** exits the app and restores normal sleep.

Artifact:

- `LidLock.dmg`
- SHA-256: `fe735f2a9cebdbd5807163d4099c75df6141d70ca36aa91265562caf1d78e8af`

## 1.1.1 - 2026-06-19

Fixed **Allow lid changes without a password** after installation.

- Corrected an installation issue that prevented the option from working.

Artifact:

- `LidLock.dmg`
- SHA-256: `fd4332c3b90b3924fe1a7fba31cde00881edbff7f6e1ddff8e96ec29dd2ce201`

## 1.1.0 - 2026-06-19 (superseded)

This build was superseded by 1.1.1 after an installation problem was found. The
public release asset was removed. Use version 1.1.1 or newer.

- Added the optional setting that allows lid changes without a password.
- Added a confirmation before requesting approval.
- Kept the normal macOS administrator prompt when **Allow lid changes without a
  password** is off.

Artifact:

- `LidLock.dmg`
- SHA-256: `09c2a796d81e1fcb8930dd30f356aca8a41413aadf66277b4f14186071d0c1b7`

## 1.0.1 - 2026-06-19

- Prevented duplicate password prompts when enabling lid closed mode on
  battery.
- Fixed cases where LidLock could reverse the selected lid setting while on
  battery.
- Kept the menu bar and main window in sync while settings change.
- Fixed Open at login cleanup while macOS approval is pending.

Artifact:

- `LidLock.dmg`
- SHA-256: `d4e2e1b97ffcf1315f8915a9519ea328dffefde65bd02f3ccd9726aa0ed44c47`

## 1.0.0 - 2026-06-19

Initial public release.

- Added signed and notarized Developer ID distribution.
- Added a direct `.dmg` download for macOS 13 or newer.
- Added controls for working with the lid shut, keeping the Mac or display
  awake, turning off the display, and restoring normal sleep.
- Runs without accounts, analytics, telemetry, or automatic network access.
- Restores normal sleep when LidLock quits and recovers the setting after an
  unexpected exit.

Artifact:

- `LidLock.dmg`
- SHA-256: `1bd59b93a726cca08aff3bf222fb70d9e88d5c680ff474e07e20714f23923799`
