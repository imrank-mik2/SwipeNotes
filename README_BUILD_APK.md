# SwipeNotes - App & Android Project

This archive contains both the standalone web app and the complete Android Studio project with GitHub Actions APK auto-build support.

## File Contents
- `index.html` - The standalone, single-file SwipeNotes web app.
- `app/src/main/assets/index.html` - The embedded asset used by the Android app.
- `app/` - The complete Android app module with native WebView wrapper.
- `.github/workflows/build-apk.yml` - Ready-to-run GitHub Action to build `app-debug.apk` in the cloud.

## Quick Ways to Generate Your APK

### 1. 1-Click Online Converter (Fastest)
1. Upload the `index.html` file to [WebIntoApp](https://www.webintoapp.com/) or [Appsgeyser](https://appsgeyser.com/).
2. Select "HTML File", enter **SwipeNotes**, and generate your ready-to-install `.apk` directly.

### 2. Free Cloud Build with GitHub Actions
1. Create a repository on GitHub and upload the contents of this zip.
2. Go to the **Actions** tab and trigger the **Build SwipeNotes APK** workflow.
3. Download the compiled `SwipeNotes-debug-apk` artifact.

### 3. Local Android Studio
1. Open this unzipped folder in **Android Studio**.
2. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
