# Build SwipeNotes APK

This package contains the complete Android WebView wrapper project and the finalized, pastel-styled SwipeNotes app (`app/src/main/assets/index.html` and `index.html`).

## Option 1: 1-Click Online Converter (No install needed)
1. You can upload the included `index.html` file to tools like **WebIntoApp** (webintoapp.com) or **Website 2 APK Builder**.
2. Select "HTML File", set the name to **SwipeNotes**, and click **Generate APK** to download the ready-to-install `.apk` directly to your phone.

## Option 2: Automatic Cloud Build via GitHub (Free, no software)
1. Create a free repository on GitHub and upload the files from this zip.
2. The included GitHub Action (`.github/workflows/build-apk.yml`) runs automatically on push.
3. Download **SwipeNotes-debug-apk** (`app-debug.apk`) directly from the GitHub **Actions** tab artifacts.

## Option 3: Local Android Studio
1. Open **Android Studio** and choose **Open** on this project folder.
2. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)** to generate `app-debug.apk`.
