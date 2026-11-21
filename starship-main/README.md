# Starship Snowflake — macOS

Native wallpaper app for macOS, built with Swift and AppKit.

## Features
- Browse the Starship GitHub wallpaper collection. Gallery files download only when selected.
- Import wallpapers from your Mac. Imported files are stored in `~/Applications/Snowflake`.
- Set animated video wallpapers across your displays.
- Control wallpaper volume from the app or the snowflake menu bar menu.
- Start at login using `SMAppService`.

## Build
Build with Xcode Command Line Tools installed. The app targets macOS Ventura (13) and later on Apple Silicon:

```bash
./Scripts/build.sh
open build/starship.app
```

The build creates `build/starship.app` and `build/starship.dmg`.
