# Pathfolio Android

This Android Studio project packages the Pathfolio HTML app and adds native PDF actions.

## Build

1. Install Android Studio.
2. Open the `Pathfolio_Android_Native` folder.
3. Let Gradle Sync finish and install Android SDK 35 if prompted.
4. Connect an Android phone with USB debugging enabled.
5. Choose **Run > Run 'app'** for testing.
6. To create an APK, choose **Build > Build App Bundles or APKs > Build APKs**.

The debug APK will be written under `app/build/outputs/apk/debug/`.

## Native PDF behavior

- **Share or save PDF** opens Android's native share sheet.
- **Open PDF / Print** opens the generated PDF in an installed PDF viewer, where Android printing is available.
- A native Save action uses Android's document picker, so no broad storage permission is required.

The web content is stored in `app/src/main/assets/index.html`.
