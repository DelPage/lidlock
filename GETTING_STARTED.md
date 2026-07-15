# Getting Started With LidLock

LidLock is a macOS menu bar utility that gives you clear control over when your
Mac and its display sleep. It is free to use, requires no account, and does not
collect personal information.

The current public download is version 1.1.3. The guided setup and four mode
interface described below are being tested for the next signed update.

## Install LidLock

1. [Download LidLock.dmg](https://github.com/DelPage/lidlock/releases/latest/download/LidLock.dmg).
2. Open the disk image and move LidLock to the Applications folder.
3. Open LidLock from Applications.
4. macOS verifies that the app is signed and notarized by DelPage Technologies.

Moving LidLock to Applications is required only for the optional password free
helper. The rest of the app can run without that helper.

## First Launch

The next LidLock update opens with a three step guide:

1. **Choose a mode.** Learn what happens to the Mac and display in each mode.
2. **Walk Away and menu bar.** Learn how to hide the screen immediately and how
   LidLock stays available after its window closes.
3. **Permissions.** See which features need no special access, why Lid Closed
   needs administrator approval, and which options are completely optional.

You can reopen this guide anytime from **Settings**, then **Getting Started**.

## The Four Modes

Only one mode can be active at a time.

| Mode | What happens |
|---|---|
| **Normal Sleep** | The Mac and display use their usual sleep settings. |
| **Lid Closed** | The Mac keeps running with the lid shut, and screens turn off. |
| **Stay Awake** | Work keeps running, but the display may turn off. |
| **Keep Screen On** | Both the Mac and display remain awake. |

**Walk Away** is a separate privacy action. It turns the screen off immediately
without stopping your work. When the display wakes, LidLock restores the mode
that was active before Walk Away.

Closing the LidLock window does not quit the app. LidLock stays available in the
macOS menu bar until you choose **Quit LidLock**.

## Permissions and Approvals

| Feature | What macOS may request | Why |
|---|---|---|
| Normal Sleep, Stay Awake, Keep Screen On, and Walk Away | Nothing | These use standard local power controls that do not require special access. |
| Lid Closed | Administrator approval | This mode changes a system wide lid sleep setting so the Mac can continue running with the lid shut. macOS protects that setting. |
| Password Free Lid Control | Optional helper approval | The signed helper avoids repeated password prompts. It can change only the lid sleep setting and accepts requests only from the signed LidLock app. |
| Launch at Login | Optional approval under Login Items | macOS lets you decide which apps may open when you sign in. |

LidLock does not request access to your files, screen contents, camera,
microphone, location, contacts, or Accessibility controls.

### Why Lid Closed Needs Administrator Approval

Lid Closed changes a setting that applies to the entire Mac, not only to the
LidLock window. macOS therefore requires administrator approval when that
setting is turned on or returned to normal.

Before the macOS approval prompt appears, LidLock explains what will change and
reminds you that the Mac may continue using power while the lid is shut. This
approval does not give LidLock access to personal information or other apps.

### Optional Password Free Helper

Without the helper, macOS may ask for an administrator password when Lid Closed
is turned on or off. If you prefer fewer prompts, open **Settings** and enable
**Password Free Lid Control**.

The helper is optional. It is signed, limited to the lid sleep setting, and can
be removed by turning the same setting off. All other LidLock features work
without it.

### Optional Launch at Login

Launch at Login is off until you enable it. macOS may ask you to approve LidLock
under **System Settings**, **General**, **Login Items**. This approval only lets
LidLock open after you sign in.

## Return to Normal

Choose **Normal Sleep** to return to the usual macOS sleep behavior. LidLock also
restores normal sleep on a clean quit by default.

If you want to remove LidLock, choose Normal Sleep first, quit the app, and move
LidLock from Applications to the Trash.

For more detail, read the [privacy policy](PRIVACY.md) or open a
[support issue](https://github.com/DelPage/lidlock/issues).
