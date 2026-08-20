# Changelog

This changelog lists every notable public LidLock release.

## 1.2.2 - 2026-08-20

- Added clear guidance before starting or ending Stay Awake with Lid Closed
  when administrator approval may be required.
- Added prompts that can open Login Items when the optional lid approval or
  Open at login needs approval in System Settings.
- Added safer quit guidance when normal sleep cannot be restored or the lid
  setting would remain on after LidLock quits.
- Expanded the first launch guide and Settings permissions section so people
  can see which actions need approval before using them.

Artifact:

- `LidLock.dmg`
- SHA-256: `7972ce8f12760ec576b0d72eff97d0731057e9de36c317dca45cde12a86a3d1a`

## 1.2.1 - 2026-08-20

- Renamed the lid-closed mode to **Stay Awake with Lid Closed**.
- The mode no longer issues a display sleep command when the lid closes. This
  removes LidLock's direct Lock Screen trigger. macOS Lock Screen settings still
  apply.
- LidLock reads the lid-close sleep setting back before showing **Active** and
  holds a stronger system sleep assertion while the mode is active.

Artifact:

- `LidLock.dmg`
- SHA-256: `3c760d3c33c738e73f24442422a9aed4bd8201aefdd6800afbf26bc24f642bc2`

## 1.2.0 - 2026-08-20

- Replaced separate power switches with four clear sleep modes.
- Added **Keep Running with Lid Closed** so the Mac and apps continue after the
  lid closes while all displays turn off.
- Added a first launch guide for modes, Walk Away, the menu bar, and approvals.
- Made Walk Away a separate action that turns off the display without stopping work.
- Added the Support LidLock page and donation choices.
- Signed and notarized both the app and disk image. Release checks require
  Gatekeeper to accept both before we publish a release.

Artifact:

- `LidLock.dmg`
- SHA-256: `56fcf464a2937557661f1b2c49d8f8d1ec465ac9dee36a9415e239a7c37e8a95`

## 1.1.3 - 2026-07-15

- Closing the main window now leaves LidLock running in the macOS menu bar.
- Hovering over the menu-bar icon shows the current sleep setting.
- **Open LidLock** brings the window back.
- **Quit LidLock** exits the app and runs its normal sleep cleanup.

Artifact:

- `LidLock.dmg`
- SHA-256: `fe735f2a9cebdbd5807163d4099c75df6141d70ca36aa91265562caf1d78e8af`

## 1.1.1 - 2026-06-19

Helper hotfix release.

- Fixed the password-free helper rejecting LidLock after install because the
  helper did not request its signing Team ID from Security.framework.
- Added a release check that fails if the helper cannot read the expected Team
  ID before notarization.

Artifact:

- `LidLock.dmg`
- SHA-256: `fd4332c3b90b3924fe1a7fba31cde00881edbff7f6e1ddff8e96ec29dd2ce201`

## 1.1.0 - 2026-06-19 (superseded)

Password-free lid control release.

This build was superseded by 1.1.1 after a helper validation bug was found. The
public release asset was removed; use 1.1.1 or newer.

- Added an optional signed helper in Settings so lid-close behavior can change
  without asking for the administrator password every time.
- Added a warning dialog before installing the helper.
- Kept the normal macOS admin prompt as the fallback when the helper is off.
- Added release checks that fail if the helper or launchd plist is missing from
  the signed app.

Artifact:

- `LidLock.dmg`
- SHA-256: `09c2a796d81e1fcb8930dd30f356aca8a41413aadf66277b4f14186071d0c1b7`

## 1.0.1 - 2026-06-19

Maintenance release.

- Fixed a battery safety path that could ask for administrator approval twice
  after enabling lid-close behavior while unplugged.
- Kept an intentional lid-close choice from being reversed during the same
  battery session.
- Improved menu/window state consistency while privileged operations are in
  progress.
- Fixed Open at login cleanup when macOS leaves the login item in a pending
  approval state.

Artifact:

- `LidLock.dmg`
- SHA-256: `d4e2e1b97ffcf1315f8915a9519ea328dffefde65bd02f3ccd9726aa0ed44c47`

## 1.0.0 - 2026-06-19

Initial public release.

- Added signed and notarized Developer ID distribution.
- Added direct `.dmg` download for macOS 13+.
- Added controls for working with the lid shut, keeping the Mac or display
  awake, turning off the display immediately, and restoring normal sleep.
- Added local-only privacy posture with no accounts, analytics, telemetry, or automatic network access during normal operation.
- Added startup and quit safeguards for restoring normal sleep state after crashes or canceled restores.

Artifact:

- `LidLock.dmg`
- SHA-256: `1bd59b93a726cca08aff3bf222fb70d9e88d5c680ff474e07e20714f23923799`
