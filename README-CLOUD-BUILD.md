# Build Shree Solar Services APK using only a phone

This ZIP contains the Android project plus a GitHub Actions workflow that builds the APK in GitHub's cloud. The ZIP itself is not an APK.

1. On your phone, sign in or create an account at https://github.com.
2. Create a new repository. You may name it `Shree-Solar-Services`.
3. Upload/extract the contents of this ZIP into the repository root (the files `settings.gradle.kts`, `build.gradle.kts`, `gradle.properties`, `app/`, and `.github/` must be at the repository root).
4. Open the repository's **Actions** tab.
5. Select **Build Shree Solar Services APK** and tap **Run workflow**.
6. Wait for the workflow to finish successfully.
7. Open that completed run, scroll to **Artifacts**, and download `Shree-Solar-Services-APK`.
8. Extract the downloaded artifact ZIP. Install `app-debug.apk` on your Android 13 phone. If Android asks, allow your browser/file manager to install unknown apps.

The app's `minSdk` is 23 and `targetSdk` is 35, so Android 13 (API 33) is within its supported range. This workflow creates a debug-signed APK for testing, not a Play Store release.
