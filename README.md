# Sales Tracker (Flutter) - Ready-to-use package

This package contains the app source (Dart) and `pubspec.yaml`.  
It is prepared for non-developers: follow these steps to produce an Android APK.

## Steps (simple)
1. Install Flutter (see https://flutter.dev/docs/get-started/install) and Android Studio.
2. Unzip this folder to a location on your PC.
3. Open a terminal inside the unzipped folder and run:

   ```bash
   flutter create .
   flutter pub get
   flutter build apk --release
   ```

4. After a successful build, the release APK will be at:
   ```
   build/app/outputs/flutter-apk/app-release.apk
   ```

5. Copy the APK to your Android phone and install it (you may need to enable 'Install unknown apps').

## Notes
- All amounts show `Ksh` prefix in the app UI and in generated PDF reports.
- The app stores data locally on the device using SQLite (no cloud sync).
- If you want me to build the APK for you and provide the file directly, I can guide you through the minimal additional steps required for me to do that (you'd need to allow upload of files to a build environment or provide remote access). Alternatively I can walk you through each step.

If anything fails, paste the terminal output here and I will troubleshoot.
