# Getting Started With LidLock

LidLock is a macOS menu bar utility for controlling when your Mac and display
sleep. It is free to use, requires no account, and does not collect personal
information.

The current public download is version 1.2.1.

## Install LidLock

1. [Download LidLock.dmg](https://github.com/DelPage/lidlock/releases/latest/download/LidLock.dmg).
2. Open the disk image and move LidLock to the Applications folder.
3. Open LidLock from Applications.
4. macOS checks that DelPage Technologies signed the app and Apple notarized it.

Move LidLock to Applications when you want the optional password-free helper.
The rest of the app can run without that helper.

## First Launch

On first launch, LidLock explains each sleep option and Walk Away. It also shows
where to find LidLock after you close its window. The guide explains why Stay
Awake with Lid Closed needs an administrator password.

You can reopen this guide anytime from **Settings**, then **Getting Started**.

## Sleep Options

| Mode | What happens |
|---|---|
| **Normal Sleep** | Uses your Mac's normal sleep settings. |
| **Stay Awake with Lid Closed** | Keeps the Mac awake after you close the lid. Your Lock Screen settings still apply. |
| **Stay Awake** | Keeps your work running while the display can turn off. |
| **Keep Screen On** | Keeps the Mac and display awake while the lid is open. |

**Walk Away** turns the display off without stopping your work. Your
previous sleep setting remains selected when the display wakes.

Closing the LidLock window does not quit the app. LidLock stays available in the
macOS menu bar until you choose **Quit LidLock**.

### Stay Awake with Lid Closed

When you choose **Stay Awake with Lid Closed**, LidLock reads the lid-close
sleep setting back before it shows **Active**. While the mode is active, LidLock
holds a stronger system sleep assertion to help keep the Mac awake.

In version 1.2.1, the mode no longer issues a display sleep command when the lid
closes. This removes LidLock's direct Lock Screen trigger. Your macOS Lock Screen
settings still apply.

## Permissions and Approvals

| Feature | What macOS may request | Why |
|---|---|---|
| Normal Sleep, Stay Awake, Keep Screen On, and Walk Away | Nothing | They work as soon as LidLock opens. |
| Stay Awake with Lid Closed | Administrator password | macOS protects changes to how the Mac sleeps with its lid shut. |
| Password-free lid control | Optional helper approval | The signed helper can change only the lid sleep setting. |
| Open at login | Optional approval under Login Items | macOS lets you decide which apps open when you sign in. |

LidLock does not request access to your files, screen contents, camera,
microphone, location, contacts, or Accessibility controls.

### Why Stay Awake with Lid Closed Needs Administrator Approval

Stay Awake with Lid Closed changes how the Mac sleeps when you close its lid.
macOS asks for an administrator password when that setting changes.

Before the password prompt appears, LidLock explains what will change. The Mac
can stay awake while you keep the lid closed. This does not give
LidLock access to your files, screen, or other apps.

### Optional Password-free Helper

Without the helper, macOS may ask for an administrator password when you turn
Stay Awake with Lid Closed on or off. If you prefer fewer prompts, open
**Settings** and enable **Use password-free lid control**.

The helper is optional. DelPage Technologies signs it, and it changes only the
lid sleep setting. Turn the same setting off to remove it. All other LidLock
features work without the helper.

### Optional Open at Login

Open at login is off until you enable it. macOS may ask you to approve LidLock
under **System Settings**, **General**, **Login Items**. This approval only lets
LidLock open after you sign in.

## Replace Older Copies

When you update LidLock, remove older copies before installing the new version:

1. Choose **Normal Sleep** in the copy you are currently using.
2. Turn off **Use password-free lid control** and **Open at login** in Settings.
3. Choose **Quit LidLock** from the menu bar.
4. Remove every `LidLock.app` from Applications, your user Applications folder, and Downloads.
5. Eject every mounted LidLock disk image.
6. Open the latest `LidLock.dmg` and move LidLock to the main Applications folder.
7. Confirm that the main Applications folder contains the only installed copy.

These steps prevent an older copy from opening at login or appearing in search.

## Return to Normal

Choose **Normal Sleep** to return to the usual macOS sleep behavior. LidLock also
restores normal sleep on a clean quit by default.

To remove LidLock, choose Normal Sleep first, quit the app, and move LidLock from
Applications to the Trash.

For more detail, read the [privacy policy](PRIVACY.md) or open a
[support issue](https://github.com/DelPage/lidlock/issues).
