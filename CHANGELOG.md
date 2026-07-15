# Changelog

All notable public releases of LidLock are tracked here.

## 1.1.3 - 2026-07-15

Menu-bar workflow release.

- Closing the main window now leaves LidLock running in the macOS menu bar.
- Added a state-aware menu-bar tooltip that shows the current protection status
  and points users to the menu controls.
- Kept **Open LidLock** and **Quit LidLock** in the menu so hiding the window and
  exiting the app are separate, predictable actions.
- Consolidated public distribution around this GitHub repository and its signed
  DMG releases.

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

- Added an optional signed privileged helper in Settings so Survive Lid Close
  can turn on and off without asking for the admin password every time.
- Added a warning dialog before installing the helper.
- Kept the normal macOS admin prompt as the fallback when the helper is off.
- Added release checks that fail if the helper or launchd plist is missing from
  the signed app.

Artifact:

- `LidLock.dmg`
- SHA-256: `09c2a796d81e1fcb8930dd30f356aca8a41413aadf66277b4f14186071d0c1b7`

## 1.0.1 - 2026-06-19

Maintenance release.

- Fixed a restore-on-battery policy path that could ask for admin approval a
  second time immediately after enabling Survive Lid Close while on battery.
- Kept explicit Survive Lid Close enables from being auto-undone during the
  same battery session.
- Improved menu/window state consistency while privileged operations are in
  progress.
- Fixed Launch at Login cleanup when macOS leaves the login item in a pending
  approval state.

Artifact:

- `LidLock.dmg`
- SHA-256: `d4e2e1b97ffcf1315f8915a9519ea328dffefde65bd02f3ccd9726aa0ed44c47`

## 1.0.0 - 2026-06-19

Initial public release.

- Added signed and notarized Developer ID distribution.
- Added direct `.dmg` download for macOS 13+.
- Added Survive Lid Close, Keep System Awake, Keep Display Awake, Walk Away, Turn Off Display, and Restore Normal Sleep controls.
- Added local-only privacy posture with no accounts, analytics, telemetry, or automatic network access during normal operation.
- Added startup and quit safeguards for restoring normal sleep state after crashes or canceled restores.

Artifact:

- `LidLock.dmg`
- SHA-256: `1bd59b93a726cca08aff3bf222fb70d9e88d5c680ff474e07e20714f23923799`
