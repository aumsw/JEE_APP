# JEE Main Mock Test — Android WebView App

This Android Studio project opens https://aumsw.github.io/jee/ inside a full-screen Android app.

## Features
- App name: JEE Main Mock Test
- Full-screen immersive display (hides Android status/navigation bars while the app is active)
- Website stays inside the app
- JavaScript and DOM storage enabled for the mock-test website
- Back button navigates within the website
- Screen stays awake during the test
- Internet permission included

## Build the APK
1. Install Android Studio (current stable version) on Windows/Mac/Linux.
2. Extract this ZIP.
3. Open the `JEE_Main_Mock_Test_Android` folder in Android Studio.
4. Allow Gradle sync to finish. If prompted, install Android SDK Platform 35.
5. Select **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
6. Android Studio will show a notification. Click **locate** to find `app-debug.apk`.
7. Copy the APK to your Android phone and install it. If Android asks, allow installing apps from that source.

## Important
- This is a WebView wrapper, not an offline copy of the website. Internet is required.
- The website content and exam functionality remain hosted at GitHub Pages.
- The first Gradle sync/build requires an internet connection.
- To change the website address, edit `HOME_URL` in `MainActivity.java`.
