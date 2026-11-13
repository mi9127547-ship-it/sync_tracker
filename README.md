# sync_tracker

![Flutter](https://img.shields.io/badge/Flutter-Material%203-02569B?logo=flutter&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows%20x64%20%7C%20Android%20arm64-brightgreen)
![Database](https://img.shields.io/badge/Database-SQLite-003B57?logo=sqlite&logoColor=white)

A cross-platform **Material 3** academic management application built with Flutter and local SQLite persistence for organizing coursework, tasks, and schedules across desktop and mobile.

## Features
- **Material 3 Interface:** Clean, adaptive UI designed for both desktop windows and mobile touchscreens.
- **Offline-First Local Storage:** Fast, reliable data persistence powered by SQLite (`sqflite` on Android and FFI on Windows).
- **Cross-Platform Binaries:** Pre-compiled standalone builds for Windows (`x64`) and Android (`arm64`).

## Installation & Usage

### Windows (`x64`)
1. Download **`sync_tracker-v1.0.0-windows-x64.zip`** from the repository files or the **Releases** section.
2. Extract the entire `.zip` folder (keep `sync_tracker.exe`, the `data` folder, and all `.dll` files together).
3. Double-click **`sync_tracker.exe`** to launch the application.

### Android (`arm64`)
1. Download **`sync_tracker-v1.0.0-android-arm64.apk`** on your Android device.
2. Tap the `.apk` file and allow installation from your browser/file manager if prompted.
3. Open **sync_tracker** from your app drawer.

## Tech Stack
- **Framework:** Flutter (Dart)
- **Database:** `sqflite` (SQLite FFI for Windows)
- **Packages:** `uuid`, `intl`
