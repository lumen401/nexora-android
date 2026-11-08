NEXORA ANDROID - build steps (no Android Studio needed)

1. Go to github.com, make a NEW repository called nexora-android (don't use your lumen repo).
2. Upload everything from this folder to it, including the .github folder.
   (If the .github folder won't upload: Add file > Create new file, name it
   .github/workflows/build-apk.yml and paste the contents of that file.)
3. Open the Actions tab > "Build Nexora APK" > Run workflow. Wait about 5 minutes.
4. Open the finished run, scroll to Artifacts, download "Nexora-apk" (a zip).
5. Unzip it. app-debug.apk is the app. Send it to your phone and install it
   (Android will ask you to allow installing from unknown sources).
