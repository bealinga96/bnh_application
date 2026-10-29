# BNH POS (Android)

1. Create a new GitHub repository and upload ALL files in this folder
   (including the hidden `.github` folder).
2. Open the repo's **Actions** tab -> **Build Android APK** -> wait for the green check
   (about 5-8 minutes). You can also press **Run workflow**.
3. Open the finished run, scroll to **Artifacts**, download **BNH-POS-apk** (a zip),
   unzip it to get `app-debug.apk`.
4. Copy the APK to the tablet, open it, and allow "Install unknown apps" when asked.

The app's code is in `www/index.html`. Edit it, commit, and the APK rebuilds.
