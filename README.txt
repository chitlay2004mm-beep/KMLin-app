KM Lin Android project (APK build source)

This is an Android Studio project wrapper for the KM Lin offline ledger HTML app.
To build an installable APK:
1. Install Android Studio on a Windows/Mac/Linux computer.
2. Open this project folder (KMLinAndroid) in Android Studio.
3. Allow Gradle sync; install Android SDK Platform 35 if prompted.
4. Choose Build > Build APK(s).
5. The debug APK will be created at app/build/outputs/apk/debug/app-debug.apk.
6. Transfer APK to your Android phone and install it (allow installing from that source if prompted).

The app uses a local WebView and embeds the HTML asset. No Internet permission is requested.
