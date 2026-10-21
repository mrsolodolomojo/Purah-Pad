# Purah Pad OS // Android APK & Project Bundle

This archive contains everything needed to compile **Purah Pad OS (Tears of the Kingdom Companion)** into a native Android `.apk`.

---

## 🚀 Option 1: Zero-Install Cloud APK Build (GitHub Actions)
You don't need to install Android Studio! GitHub's servers will build the `.apk` for you automatically:

1. Create a new repository on [GitHub](https://github.com/new).
2. Upload the contents of this unzipped folder to the repository (**make sure the hidden `.github/workflows/build-apk.yml` folder is included**).
3. Click the **Actions** tab at the top of your GitHub repository.
4. Click the **Build Purah Pad OS APK** workflow run and wait ~2 minutes for it to finish.
5. Scroll to the **Artifacts** section at the bottom of the workflow summary and download **`Purah-Pad-OS-APK.zip`**.
6. Unzip it and install **`app-debug.apk`** on your Android phone or tablet!

---

## 🛠️ Option 2: Local Android Studio Build (Kotlin WebView)
If you use Android Studio locally:
1. Open the `android-studio-project` files inside Android Studio (or copy `MainActivity.kt`, `AndroidManifest.xml`, and `assets/index.html` into an Empty Views Activity project).
2. Click **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

---

## ✨ Android Native Enhancements Included
- **Two-Finger Pinch-to-Zoom**: Smoothly zoom the Sky, Surface, and Depths map canvas between `0.045x` and `0.45x` anchored around your fingers.
- **Android Hardware Back Gesture**: Pressing Back closes open modals, the Pin Inspector drawer, or exits Stamp/Route mode before closing the app.
- **Persistent Offline Storage**: `domStorageEnabled = true` preserves all Shrines, Lightroots, Dragon's Tears, Armor upgrades, and Custom Stamps.
