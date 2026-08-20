# Getting Started With LidLock

LidLock is a macOS menu bar utility for controlling when your Mac and display
sleep. It is free to use, requires no account, and does not collect personal
information.

The current public download is version 1.2.2.

## Install LidLock

1. [Download LidLock.dmg](https://github.com/DelPage/lidlock/releases/latest/download/LidLock.dmg).
2. Open the disk image and move LidLock to the Applications folder.
3. Open LidLock from Applications.
4. macOS checks that DelPage Technologies signed the app and Apple notarized it.

Install LidLock in Applications if you want to allow lid changes without a
password. The other controls do not need that approval.

## First Launch

The setup guide explains the sleep options, Walk Away, menu bar access, and
approvals. LidLock also explains any required approval before it changes a
protected setting.

Reopen the guide from **Settings**, then **Getting Started**.

## Sleep Options

| Mode | What happens |
|---|---|
| **Normal Sleep** | Uses your Mac's normal sleep settings. |
| **Stay Awake with Lid Closed** | Keeps the Mac awake after you close the lid. Your Lock Screen settings still apply. |
| **Stay Awake** | Keeps your work running while the display can turn off. |
| **Keep Screen On** | Keeps the Mac and display awake while the lid is open. |

**Walk Away** turns the display off without stopping your work. Your previous
sleep setting remains selected when the display wakes.

Closing the LidLock window does not quit the app. LidLock stays in the menu bar
until you choose **Quit LidLock**.

### Stay Awake with Lid Closed

Use this mode when work needs to continue after you close the lid. Your macOS
Lock Screen settings still apply.

## Permissions and Approvals

| Feature | What macOS may request | Why |
|---|---|---|
| Normal Sleep, Stay Awake, Keep Screen On, and Walk Away | Nothing | Available as soon as LidLock opens. |
| Stay Awake with Lid Closed | Administrator password unless **Allow lid changes without a password** is enabled | macOS protects changes to lid sleep behavior. |
| Allow lid changes without a password | Approval in Login Items | Avoids password prompts for lid changes. |
| Open at login | Approval in Login Items | Lets LidLock open when you sign in. |

If macOS needs approval, LidLock explains why and can open Login Items. Settings
shows **Waiting for approval** until the request is enabled.

LidLock does not request access to your files, screen contents, camera,
microphone, location, contacts, or Accessibility controls.

### Administrator Approval

Stay Awake with Lid Closed changes how the Mac sleeps after you close the lid,
so macOS may ask for an administrator password. LidLock explains the change and
lets you continue or cancel before the password prompt appears.

The same approval may be needed when you return to Normal Sleep. It does not
give LidLock access to your files, screen, or other apps.

### Allow Lid Changes Without a Password

Turn on **Allow lid changes without a password** in Settings if you want fewer
password prompts. macOS may ask you to approve LidLock under **System Settings**,
**General**, **Login Items**. LidLock can open that page for you.

This option changes only lid sleep behavior. Turn it off to remove the approval.
All other LidLock features work without it.

### Open at Login

Open at login is off until you enable it. If macOS needs approval, LidLock shows
an **Open Login Items** button. This approval only lets LidLock open after you
sign in.

## Replace Older Copies

When you update LidLock, remove older copies before installing the new version:

1. Choose **Normal Sleep** in the copy you are currently using.
2. Turn off **Allow lid changes without a password** and **Open at login** in Settings.
3. Choose **Quit LidLock** from the menu bar.
4. Remove every `LidLock.app` from Applications, your user Applications folder, and Downloads.
5. Eject every mounted LidLock disk image.
6. Open the latest `LidLock.dmg` and move LidLock to the main Applications folder.
7. Confirm that the main Applications folder contains the only installed copy.

These steps prevent an older copy from opening at login or appearing in search.

## Return to Normal

Choose **Normal Sleep** to restore the usual macOS sleep behavior. LidLock also
restores normal sleep when it quits by default.

To remove LidLock, choose Normal Sleep first, quit the app, and move LidLock from
Applications to the Trash.

For more detail, read the [privacy policy](PRIVACY.md) or open a
[support issue](https://github.com/DelPage/lidlock/issues).
