# Minecraft City Planner — Android APK project

This project wraps the existing HTML planner in a simple Android WebView and builds a debug APK using GitHub Actions.

## Build
1. Upload the contents of this folder to the root of your GitHub repository, preserving folders.
2. Open the repository's **Actions** tab.
3. If prompted, enable Actions.
4. Open **Build Android APK** and tap **Run workflow** (or push a commit to `main`).
5. When the workflow completes, open its run and download the `Minecraft-City-Planner-APK` artifact.
6. Extract the artifact ZIP on Android; install `app-debug.apk`.

The APK is unsigned for Play Store release, but is suitable for installing on your own device. Android may ask permission to install apps from the browser/files app.

Note: the planner HTML uses browser storage. WebView storage is local to the installed app and is separate from Chrome's storage.
