# Changelog

All notable public releases of LidLock are tracked here.

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
- Added public Homebrew tap support with `brew install --cask imwalkinhere/lidlock/lidlock`.
- Added Survive Lid Close, Keep System Awake, Keep Display Awake, Walk Away, Turn Off Display, and Restore Normal Sleep controls.
- Added local-only privacy posture with no accounts, analytics, telemetry, or automatic network access during normal operation.
- Added startup and quit safeguards for restoring normal sleep state after crashes or canceled restores.

Artifact:

- `LidLock.dmg`
- SHA-256: `1bd59b93a726cca08aff3bf222fb70d9e88d5c680ff474e07e20714f23923799`
