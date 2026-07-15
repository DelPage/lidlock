# Getting Started With LidLock

LidLock is a macOS menu bar utility for controlling when your Mac and display
sleep. It is free to use, requires no account, and does not collect personal
information.

The current public download is version 1.1.3. The guided setup and four mode
interface described below are being tested for the next signed update.

## Install LidLock

1. [Download LidLock.dmg](https://github.com/DelPage/lidlock/releases/latest/download/LidLock.dmg).
2. Open the disk image and move LidLock to the Applications folder.
3. Open LidLock from Applications.
4. macOS verifies that the app is signed and notarized by DelPage Technologies.

Moving LidLock to Applications is required only for the optional password-free
helper. The rest of the app can run without that helper.

## First Launch

On first launch, LidLock shows what each sleep option does, how Walk Away works,
where to find LidLock after closing its window, and why Lid Closed needs an
administrator password.

You can reopen this guide anytime from **Settings**, then **Getting Started**.

## Sleep Options

| Mode | What happens |
|---|---|
| **Normal Sleep** | Uses your Mac's normal sleep settings. |
| **Lid Closed** | Keeps your Mac working with the lid shut while displays turn off. |
| **Stay Awake** | Keeps your work running while the display can turn off. |
| **Keep Screen On** | Keeps the Mac and display awake. |

**Walk Away** turns the display off immediately without stopping your work. Your
previous sleep setting remains selected when the display wakes.

Closing the LidLock window does not quit the app. LidLock stays available in the
macOS menu bar until you choose **Quit LidLock**.

## Permissions and Approvals

| Feature | What macOS may request | Why |
|---|---|---|
| Normal Sleep, Stay Awake, Keep Screen On, and Walk Away | Nothing | They work as soon as LidLock opens. |
| Lid Closed | Administrator password | macOS protects changes to how the Mac sleeps with its lid shut. |
| Password-free lid control | Optional helper approval | The signed helper can change only the lid sleep setting. |
| Open at login | Optional approval under Login Items | macOS lets you decide which apps open when you sign in. |

LidLock does not request access to your files, screen contents, camera,
microphone, location, contacts, or Accessibility controls.

### Why Lid Closed Needs Administrator Approval

Lid Closed changes how the entire Mac sleeps when its lid is shut. macOS asks
for an administrator password when that setting changes.

Before the password prompt appears, LidLock explains what will change and that
the Mac will continue using power while the lid is shut. This does not give
LidLock access to your files, screen, or other apps.

### Optional Password-free Helper

Without the helper, macOS may ask for an administrator password when Lid Closed
is turned on or off. If you prefer fewer prompts, open **Settings** and enable
**Use password-free lid control**.

The helper is optional. It is signed, limited to the lid sleep setting, and can
be removed by turning the same setting off. All other LidLock features work
without it.

### Optional Open at Login

Open at login is off until you enable it. macOS may ask you to approve LidLock
under **System Settings**, **General**, **Login Items**. This approval only lets
LidLock open after you sign in.

## Return to Normal

Choose **Normal Sleep** to return to the usual macOS sleep behavior. LidLock also
restores normal sleep on a clean quit by default.

If you want to remove LidLock, choose Normal Sleep first, quit the app, and move
LidLock from Applications to the Trash.

For more detail, read the [privacy policy](PRIVACY.md) or open a
[support issue](https://github.com/DelPage/lidlock/issues).
