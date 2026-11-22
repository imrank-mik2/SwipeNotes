# SwipeNotes

Focus on one card at a time. A minimalist, gesture-driven pastel task and routine management app.

---

## Overview

**SwipeNotes** is designed to replace cluttered, intimidating to-do lists with a calm, tactile experience. Drawing inspiration from cards and natural touch gestures, your routines, checklists, and daily priorities are presented as clean pastel cards that you can swipe through seamlessly.

Whether organizing morning habits, checking off daily errands, or reviewing quick notes, SwipeNotes keeps you focused on one thing at a time.

---

## Features

- **Gesture-Driven Card Stack**: Swipe left or right through cards with natural physics and smooth transitions.
- **Calming Pastel Aesthetics**: Soft pastel palettes (Peach, Lavender, Mint, Sky, and Blush) that reduce digital visual fatigue.
- **Interactive Checklists**: Simple markdown-style checkboxes `[]` and `()` that toggle with a single tap.
- **Offline First & Persistent**: Data saves directly to device storage via HTML5 LocalStorage and LevelDB/SQLite in Android WebView, preserving your cards across reboots.
- **Multi-Platform Access**:
  - **Android Application**: Ready-to-build Android Studio project with custom launcher and adaptive icons.
  - **Standalone Web App**: Single-file web application that can run in any modern web browser without server dependencies.

---

## Architecture & Tech Stack

- **Android App**: Java, Android SDK 34 (Minimum SDK 24), AndroidX AppCompat WebView wrapper.
- **Web App**: Single-page application using HTML5, TailwindCSS, and touch gesture handling.
- **Storage**: HTML5 DOM Storage API persisted to internal flash storage.
- **Automation**: GitHub Actions CI workflow to compile `app-debug.apk` directly in the cloud.

---

## Getting Started

### 1. Cloud Build via GitHub Actions
1. Push your changes to GitHub or trigger the workflow manually under the **Actions** tab.
2. Select the **Build SwipeNotes APK** workflow.
3. Download the compiled `SwipeNotes-debug-apk` artifact from the workflow run summary.

### 2. Standalone Web App
Open `index.html` directly in your browser or host it on any static web host (such as GitHub Pages).

### 3. Build Locally with Android Studio
1. Open this repository folder in Android Studio.
2. Let Gradle sync dependencies.
3. Run or build via **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
