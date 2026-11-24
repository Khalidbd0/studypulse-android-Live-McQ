# StudyPulse Android App — How to Generate the `.apk`

## Option 1: Build APK Online via GitHub Actions (No PC / Android Studio Needed)
1. Create a free repository on GitHub and upload all files from this ZIP.
2. Go to the **Actions** tab in your repository and run **Build Android APK**.
3. Download **`StudyPulse-debug-apk`** from the workflow artifacts, extract `app-debug.apk`, and install it on your Android phone.

## Option 2: Build APK on PC with Android Studio
1. Extract this ZIP and open the folder in **Android Studio**.
2. Wait for Gradle sync, then click **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
3. Find your APK at `app/build/outputs/apk/debug/app-debug.apk`.
