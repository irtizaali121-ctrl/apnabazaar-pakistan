===.==========================================================
ApnaBazaar Pakistan — Android APK Build Instructions
=============================================================
Package ID: pk.apnabazaar.app
App Name: ApnaBazaar Pakistan
Target SDK: Android 34 (Android 14)
Minimum SDK: Android 22 (Android 5.1+)

Option 1: Build APK with Android Studio
-------------------------------------------------------------
1. Open Android Studio -> Open -> Select this project folder.
2. Wait for Gradle sync to complete.
3. Click "Build" menu -> "Build Bundle(s) / APK(s)" -> "Build APK(s)".
4. Once completed, click "locate" to get your installable:
   app-release.apk or app-debug.apk

Option 2: Build APK via Terminal Command Line (Gradle)
-------------------------------------------------------------
On Linux / Mac:
   ./gradlew assembleRelease
On Windows:
   gradlew.bat assembleRelease

Output APK will be located at:
   android/app/build/outputs/apk/release/app-release-unsigned.apk

Option 3: Automated Cloud Build (Zero PC setup)
-------------------------------------------------------------
Push this code to any GitHub repository.
Go to Actions tab -> "Build ApnaBazaar Android APK" -> Click "Run workflow".
Download the completed APK zip artifact directly from GitHub!
