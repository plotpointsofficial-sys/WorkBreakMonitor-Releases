# WorkBreak Monitor

Official Windows x64 installers and signed application updates.

## Install

Download **WorkBreakMonitorV23_Setup.exe** from [the latest release](https://github.com/plotpointsofficial-sys/WorkBreakMonitor-Releases/releases/latest), then run it. WorkBreak starts in the tray after setup and automatically after Windows sign-in. Windows may put its icon under the hidden-icons arrow.

Open License to copy your Device ID and activate or renew using a key from your license provider. In Preferences, add personal JPEG, PNG or WebP photos for your rest backgrounds. Photos and wellness records stay on your computer.

## Free application updates

WorkBreak checks after launch and daily while running. Open About WorkBreak or choose Check for Updates from the tray, then choose Download & install. No GitHub account is needed. Updates verify a cryptographic signature before installation and preserve your settings, activation, photos and history. A valid monitoring license is separate from free application upgrades.

The installer currently has no Windows Authenticode certificate, so Windows may show an unrecognized-publisher prompt. Updater signatures are enabled separately. SHA256SUMS.txt is included with each release.

Closing the dashboard keeps monitoring in the tray; choose Exit to stop it. Your records are stored under `%APPDATA%/WorkBreakMonitor`.

This repository contains release artifacts only. Application source and signing keys are maintained privately.

Developed by Michael A. Matias, CHRA, CDSMT.
