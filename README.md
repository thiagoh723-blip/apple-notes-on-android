# Apple Notes on Android

A lightweight Android wrapper for iCloud Notes. It opens `https://www.icloud.com/notes` in an immersive full-screen WebView and routes non-web links to Chrome when available.

## Build

Open this folder in Android Studio, sync Gradle, and run the `app` configuration on an Android device or emulator. The project uses Android Gradle Plugin 8.7.3, JDK 17, and Android SDK 35.

## Sign-in note

The iCloud page runs inside a WebView to provide the full-screen app experience. If Apple requires a full browser for sign-in, open the iCloud Notes link in Chrome. Android does not let this app hide Chrome's own interface.
