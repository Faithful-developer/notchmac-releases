# notchmac

A notch companion for MacBooks with a notch: a **Shelf** for files you are moving between apps,
a **Now Playing** player, a timer, a to-do list and a mirror, all in the notch.

This repository holds the downloads and the update feed. The app updates itself, so you only
install it once.

## Install

1. Download `notchmac-<version>.dmg` from the [latest release](https://github.com/Faithful-developer/notchmac-releases/releases/latest).
2. Open the DMG and drag **notchmac** to **Applications**.
3. Open notchmac from Applications.

The first time, macOS may say it can't check notchmac for malicious software, because the app is
not notarized by Apple yet. To open it anyway:

1. Open **System Settings → Privacy & Security**.
2. Scroll down to the message about notchmac and click **Open Anyway**, then confirm.

You only do this once. Updates install without it.

Requires macOS 14 or later on a Mac with Apple silicon or Intel.

## Updates

notchmac checks for updates every few hours and installs them in the background:

- When an update is ready, the notch shows a short banner. Click it to restart into the new version now.
- Otherwise it installs on its own the next time you quit notchmac or leave your Mac idle for a few minutes.
- After an update, the notch tells you which version you are on. Click the banner to see what's new.

You can turn automatic installs off, or check right away, in **Settings → General → Updates**.
