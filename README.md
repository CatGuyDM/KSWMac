# Kirby ~ Soft & Wet — macOS build

Unofficial macOS build of [Kirby ~ Soft & Wet](https://strimps-kitchen.itch.io/kirby-soft-and-wet)
by Strimp's Kitchen. All credit to the original developer.

## Install

1. Download the .zip from Releases
2. Unzip, drag the app to Applications
3. Double-click. macOS will block it the first time.
4. System Settings → Privacy & Security → scroll down → **Open Anyway**

If it says the app is "damaged", open Terminal and run:

    xattr -cr /Applications/"Kirby ~ Soft & Wet.app"

The app is ad-hoc signed, not notarized by Apple, which is why the warning appears.
