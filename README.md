# SqueezeClip

An original Android app: pick a video, trim it, compress it, split it into 30-second parts, then save or share.
Kotlin + Jetpack Compose + Media3 Transformer. No ads, no accounts, no network use.

## Build the APK
1. Install Android Studio (current stable).
2. File > Open, choose this folder. Let Gradle sync (accept any Gradle/AGP upgrade prompt).
3. Plug in your phone (USB debugging on) and press Run, or:
   Build > Build Bundle(s) / APK(s) > Build APK(s). The file lands in app/build/outputs/apk/debug/.

Before publishing, change `applicationId` and `namespace` in app/build.gradle.kts and the package name in the Kotlin files.
