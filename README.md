# Art of Bite

Android app that wraps the live NutriScan website (https://dhaydar68.github.io/nutriscan/).
Built in the cloud with GitHub Actions, no Android Studio needed.

## How to build the APK

1. Upload everything in this folder to the root of a new GitHub repository
   (the `.github` folder must be included).
2. Open the **Actions** tab. The "Build Android APK" workflow starts on its own after the upload.
   You can also start it with **Run workflow**.
3. When the run shows a green tick, open it and download `art-of-bite-apk` from **Artifacts**.
4. Unzip it, copy `app-debug.apk` to your phone and install it
   (allow "install from unknown sources" if asked).

If the build fails, open the failed run, copy the error from the log and fix it with your AI assistant.

## Change the website address

Edit `SITE_URL` in `app/src/main/java/com/student/artofbite/MainActivity.kt`.
