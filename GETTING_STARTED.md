# LidLock help

## Install

[Download LidLock.dmg](https://github.com/DelPage/lidlock/releases/latest/download/LidLock.dmg), open it, and drag LidLock to Applications.

LidLock 1.2.6 requires macOS 13 or later. Open the app to choose a mode.

## Sleep modes

| Mode | Behavior |
|---|---|
| Normal Sleep | Follow macOS sleep settings. |
| Stay Awake with Lid Closed | Keep tasks running with the screen dark and Mac unlocked. |
| Stay Awake (Lid Open) | Keep tasks running. Let the display sleep. |
| Keep Screen On (Lid Open) | Keep the Mac and display awake. |

Closed-lid mode restores screen brightness when you open the lid. It does not change your Mac's lock settings.

**Turn Display Off** turns off the display immediately while tasks continue. This action uses your Mac's lock settings.

Closing the window leaves LidLock running in the menu bar. Choose **Open LidLock** to reopen the window or **Quit LidLock** to exit.

## Settings

- **Open at login** starts LidLock when you sign in.
- **Show in menu bar** controls the menu bar icon.
- **Show power details** shows the current sleep timers and power source.
- **Restore normal sleep on quit** ends closed-lid mode when you quit. It starts on.
- **Restore normal sleep on battery with lid closed** ends closed-lid mode on battery power. It starts off.
- **Allow lid changes without a password** saves approval for starting and ending closed-lid mode. If macOS requires approval, Settings shows **Open Login Items** beside the pending request.

Without saved approval, macOS asks for an administrator password when starting or ending closed-lid mode. Canceling that prompt cancels the change.

## Update or remove

To update, quit LidLock and replace the app in Applications with the new download.

To uninstall, choose Normal Sleep, turn off Open at login and Allow lid changes without a password, then quit and move LidLock to the Trash.

[Report a problem](https://github.com/DelPage/lidlock/issues) · [Privacy policy](PRIVACY.md)
