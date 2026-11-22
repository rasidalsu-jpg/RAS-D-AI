# RAŞİD AI Android project

This is a starter Android WebView app. It builds a debug APK with GitHub Actions.

## Build
1. Create a GitHub repository and upload all files in this folder.
2. Open the repository's Actions tab.
3. Run "Build RAŞİD AI APK" using Run workflow (or push to main).
4. Open the completed workflow run and download artifact `RASID-AI-debug-apk`.
5. Extract the artifact and install `app-debug.apk` on Android.

## Groq key
The app asks each user to enter their own Groq API key. It stores it in local WebView storage on that device. Do not embed a shared API key in the APK. For a public commercial release, use a secure backend proxy instead of direct client-side API calls.
