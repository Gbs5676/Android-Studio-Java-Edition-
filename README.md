# Android Studio Java Edition (ASJE)

An on-device Java IDE for Android: write, compile, sign and install Android apps directly from your phone, with no computer needed.

> **Note:** This project is an updated fork of **APK BUILDER** by **HEAGOO** . The original app is no longer maintained. This fork fixes bugs and updates dependencies to keep it working on modern devices (64 BIT and more recent versions of Android). All credit for the original work goes to its author.

## Features

- Java editor with syntax highlighting (Java, XML, HTML, CSS, JS, JSON, Smali, Shell)
- On-device build toolchain: ECJ compiler, AAPT, DX and APK signer
- Built-in terminal emulator
- Git support
- Project templates: Empty Activity, Settings Activity, List Activity, Web Wrapper, SQLite Demo, Flashlight, Live Wallpaper
- Multi-architecture support (ARM, ARM64, x86)

## What changed from the original

- Added 64-bit libraries  
- Updated ART references  
- Added dark theme for better readability  
- Added systems to prevent crashes on newer devices

## Installation

1. Download the latest APK.
2. Allow installation from unknown sources if prompted.
3. Open the app and grant storage permission.

## Requirements

- Android 4 or newer
- 512 MB of free storage

## Building from source

1. Clone the repository:
   ```
   git clone https://github.com/Gbs5676/Android-Studio-Java-Edition-.git
   ```
2. Open it in Android Studio (or build with your preferred tool).
3. Sign the APK with **your own keystore**. Do not commit keystores to the repository.

## Credits and licenses

- Original application: **APKBUILDER** by **HEAGOO**
- Terminal emulator: Android Terminal Emulator (jackpal), Apache License 2.0
- Rhino: Mozilla Public License 2.0
- Other third-party libraries remain under their respective licenses.


## Contributing

Bug reports and pull requests are welcome. Please open an issue first to discuss major changes.

## Disclaimer

This project is provided as is, without warranty of any kind. It is not affiliated with Google or the Android Open Source Project.
