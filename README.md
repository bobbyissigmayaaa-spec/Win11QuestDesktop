# Win11 Quest Desktop (prototype)

A Windows 11-inspired desktop shell prototype packaged as an Android WebView app.
It is designed as a starting point for a Quest 3S APK, not a real Windows emulator.

## What works in this prototype
- Windows 11-inspired wallpaper, desktop icons, taskbar, Start menu, and movable/resizable app windows
- A mock File Explorer with sample folders/files
- A Notes app that saves text in local browser storage
- A Calculator app
- A browser shortcut that opens the system browser
- Touch/controller pointer interaction through normal Android WebView input

## Important limitations
- This ZIP is an Android Studio project, **not a compiled APK**.
- It has not been built or tested on a Quest headset here.
- It simulates a desktop; it does not run Windows programs or provide a full Windows operating system.
- The app needs internet access only if you use the browser shortcut.
- For a Quest build, open the project in Android Studio, let Gradle sync, build an APK, then sideload it to the headset. You may need to adjust SDK/Gradle versions to match your installed Android Studio.

## Build
Open this folder in Android Studio. Use JDK 17 and Android SDK 35 or a compatible installed SDK.
Then choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
