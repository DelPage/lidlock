# LidLock help

## Install

[Download LidLock.dmg](https://github.com/DelPage/lidlock/releases/latest/download/LidLock.dmg), open it, and drag LidLock to Applications.

LidLock 1.3.0 requires macOS 13 or later. Open the app to choose a mode.

## Modes

All four modes keep tasks running and prevent automatic locking. Your Mac's lock settings stay unchanged.

| Mode | Screen behavior |
|---|---|
| Screen On, Lid Open | Screen stays on while the lid is open. |
| Screen Off, Lid Open | Screen goes black. Press Esc to turn it on. |
| Screen On, Lid Closed | Screen stays on when you close the lid. |
| Screen Off, Lid Closed | Screen goes black when you close the lid and comes back on when you open it. |

Choose a closed lid mode before closing the laptop. **Stop Keeping Awake** returns to normal sleep and locking.

Closing the window leaves LidLock running in the menu bar. Choose **Open LidLock** to reopen the window or **Quit LidLock** to exit.

## Settings

- **Open at login** starts LidLock when you sign in.
- **Show in menu bar** controls the menu bar icon.
- **Show power details** shows the current sleep timers and power source.
- **Restore normal sleep on quit** ends closed lid mode when you quit. It starts on.
- **Restore normal sleep on battery with lid closed** ends closed lid mode on battery power. It starts off.
- **Allow lid changes without a password** saves approval for starting and ending closed lid mode. If macOS requires approval, Settings shows **Open Login Items** beside the pending request.

Without saved approval, macOS asks for an administrator password when starting or ending closed lid mode. Canceling that prompt cancels the change.

## Update or remove

To update, quit LidLock and replace the app in Applications with the new download.

To uninstall, choose Stop Keeping Awake, turn off Open at login and Allow lid changes without a password, then quit and move LidLock to the Trash.

[Report a problem](https://github.com/DelPage/lidlock/issues) · [Privacy policy](PRIVACY.md)
