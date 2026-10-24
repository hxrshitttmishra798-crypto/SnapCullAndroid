SnapCull.ai Android wrapper project

This project wraps the current SnapCull.ai prototype in an Android WebView.
The current scan uses demo/sample data; it is not real AI photo detection and does not delete real photos.

Build an APK:
1. Upload this project folder to a new GitHub repository (the files inside SnapCullAndroid).
2. Open the repository's Actions tab.
3. Select "Build SnapCull.ai APK" and click "Run workflow" (or push to main).
4. When the workflow completes, open its run and download the artifact named "SnapCull-ai-debug-apk".
5. Unzip the artifact; app-debug.apk is the installable debug APK. On Android, allow installing unknown apps for the app you use to open it, then install.

For local build, open the folder in Android Studio and build app > Build Bundle(s) / APK(s) > Build APK(s).
