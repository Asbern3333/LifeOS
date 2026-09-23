# LifeOS Android — No Android Studio Needed

This project is set up so GitHub can build the APK for you in the cloud.

## What you do

1. Create a free GitHub account if you do not already have one.
2. Create a new repository, for example `LifeOS`.
3. Upload ALL files and folders from this project into the repository.
   Make sure `.github/workflows/build-apk.yml` is included.
4. Open the repository's **Actions** tab.
5. Open **Build LifeOS APK**.
6. Choose **Run workflow**.
7. When the build is complete, open the build run.
8. Under **Artifacts**, download **LifeOS-APK**.
9. Extract the downloaded ZIP. Inside is `LifeOS.apk`.
10. Send `LifeOS.apk` to your Samsung A10 (USB, Google Drive, email to yourself, etc.).
11. On the A10, tap `LifeOS.apk`.
12. Android may ask you to allow installs from that browser/file manager. Allow it for that source.
13. Install LifeOS.

## Important

- You do NOT need Android Studio.
- The APK is a debug APK for personal installation/testing.
- The current LifeOS interface runs locally inside the app.
- The current alarm UI is not yet a true Android background alarm.
- The AI-code-editor feature still needs a server/API and cannot directly rewrite an installed APK.
