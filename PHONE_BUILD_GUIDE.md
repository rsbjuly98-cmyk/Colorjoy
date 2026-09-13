# Build ColorJoy APK using only your phone

This package is designed for a phone-only workflow using GitHub's cloud build service.

1. Create a free GitHub account at github.com if you don't have one.
2. In your phone browser, create a new repository, for example `colorjoy`.
3. Open the repository and choose **Add file > Upload files**.
4. Unzip this package first using your phone's file manager. Upload the contents of this folder, including `.github/workflows/build-apk.yml`.
5. Commit the files to the `main` branch.
6. Open the repository's **Actions** tab.
7. Open **Build ColorJoy APK**. It should run automatically after the push. You can also use **Run workflow**.
8. Wait for the green checkmark.
9. Open the completed workflow run, scroll to **Artifacts**, and download `ColorJoy-debug-apk`.
10. Unzip the artifact and open `app-debug.apk` on your Android phone.
11. If Android asks, enable installation from that source and install.

No computer is needed for this workflow.

Important:
- This produces a debug APK for personal installation/testing.
- It is not a Play Store-signed release APK.
- The app is offline-first and does not need internet while coloring.
