LAWYER ONLINE — MOBILE GITHUB APK BUILD

This package contains:
- lawyer-online-flutter-project.zip: the Flutter project source. Upload this single ZIP to the ROOT of your new GitHub repository.
- build-apk.yml: workflow template that tells GitHub how to build the APK.
- README-MOBILE.txt: these instructions.

On your Android phone:
1. Extract this outer package.
2. Open your GitHub repository lawyer-online-flutter.
3. Tap Add file > Upload files and upload ONLY lawyer-online-flutter-project.zip. Commit the upload.
4. Tap Add file > Create new file.
5. For the filename, type exactly: .github/workflows/build-apk.yml
6. Open build-apk.yml from the extracted package in a text viewer, copy all its text, and paste it into the GitHub editor.
7. Commit changes to the main branch.
8. Open Actions, select "Build Lawyer Online APK", and open the latest run.
9. When it succeeds, download the artifact named lawyer-online-release-apk. Extract that artifact ZIP to get app-release.apk.

If the workflow fails, send me a screenshot of the error. The APK has NOT been built yet; GitHub Actions must run first.
