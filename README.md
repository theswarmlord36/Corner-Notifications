# Corner-Notifications

**Your notifications. Your corner. Your timing.**

Move Mac notification banners to any corner, hide them on a timer, or swipe them away, all while keeping your notification history.

## Download

[Download Corner Notifications for Mac](https://github.com/theswarmlord36/Corner-Notifications/releases/download/v1.1.0-beta/Corner-Notifications-1.1.0-beta.zip)

Public beta. Not notarized by Apple. See installation instructions below.

## Features

- **Choose any corner:** Top left, top right, bottom left, or bottom right.
- **Hide banners:** Keep notifications in Notification Center without leaving popups onscreen.
- **Auto-hide:** Choose 3, 5, or 10 seconds, or turn the timer off.
- **Swipe to hide:** Swipe right with two fingers to hide visible banners. Normal scrolling and navigation still reach other apps.
- **Menu bar controls:** Change settings without opening the main window.
- **Pause anytime:** Return banner placement to macOS.

## Installation

1. Download and extract the latest release.
2. Move the app into your **Applications** folder and open it.
3. Enable its access in **System Settings → Privacy & Security → Accessibility**.
4. Choose a corner to start. The app initially opens in **System default (paused)** mode.

**Public beta:** The app is not notarized by Apple. macOS may block its first launch. If you trust the download, follow [Apple’s instructions for opening an app from an unidentified developer](https://support.apple.com/102445).

## How it works

Corner Notifications uses Accessibility access to reposition notification banners. Hiding a banner moves it offscreen rather than deleting it from Notification Center.

Closing the settings window leaves the app running in the menu bar. Pausing or quitting restores the window positions it changed.

## Privacy

- No notification text is read or saved.
- No analytics or network requests.
- No keyboard monitoring.
- Settings and geometry diagnostics stay on your Mac.

The optional swipe feature observes trackpad scrolling without blocking it. Other apps may respond to the same gesture.

## Beta limitations

- Tested on macOS 26.5.1 on one Mac. Other versions and display arrangements have not yet been fully tested.
- A banner may briefly appear in its original position before moving.
- macOS may dismiss temporary banners before the selected timer expires.
- Hiding banners does not mute notification sounds.
- macOS updates may affect compatibility.
- Automatic updates are not included.

## Report a bug

Open an issue with your macOS version, display setup, selected settings, and steps to reproduce the problem. Avoid including private notification content.

## Uninstall

Quit the app, then move it from Applications to Trash. You can also remove its Accessibility permission in System Settings. Your notification history is preserved.
