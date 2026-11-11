AERO PLACEMENT TRACKER - ANDROID PROJECT

Offline-first placement tracker features:
- Daily aerospace placement checklist with editable custom tasks
- Daily completion percentage
- German / Duolingo manual progress fields (XP, streak, lessons, weekly XP, target level)
- Optional Duolingo screenshot preview (values are entered manually; no unofficial account-token integration)
- Placement milestones and daily reflection
- Local storage on the phone via WebView localStorage

BUILD WITHOUT ANDROID STUDIO (CLOUD BUILD):
This project includes .github/workflows/android.yml for GitHub Actions.
1. Sign in to GitHub and create a new repository.
2. Upload the contents of this project folder (including the hidden .github folder) to the repository.
3. Open the repository's Actions tab.
4. Select "Build Android APK" and click "Run workflow" (or push to the main branch).
5. When the workflow finishes successfully, open the run and download the artifact named "AeroPlacementTracker-debug-apk".
6. Extract the downloaded artifact ZIP to get app-debug.apk.
7. Transfer app-debug.apk to your Android phone and install it. Android may ask you to allow installs from that source.

BUILD WITH ANDROID STUDIO:
Open this folder in Android Studio and choose Build > Build Bundle(s) / APK(s) > Build APK(s).

Package: com.aerotracker.app
Minimum Android: Android 6.0 (API 23)

NOTE: GitHub Actions builds the APK in the cloud; Android Studio is not required on your computer. The app does not connect directly to Duolingo; enter progress manually or use a screenshot. Do not share Duolingo passwords, cookies, or session/JWT tokens.
