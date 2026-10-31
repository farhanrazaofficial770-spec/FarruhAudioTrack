# FARRUH AUDIO TRACK — Android Studio project

This is an Android WebView wrapper around the supplied V8.1 HTML vocal-studio build.

## Build an APK
1. Open this folder in Android Studio (recent version).
2. Allow Gradle sync and install the Android SDK Platform 35 if prompted.
3. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. The debug APK is normally created at `app/build/outputs/apk/debug/app-debug.apk`.

## Included
- V8.1 HTML app bundled offline in `app/src/main/assets/index.html`
- Supplied Farhan logo and creator credit
- Android microphone permission bridge
- Audio-file picker bridge
- Original dark studio interface retained

## Important limitations
This package is a WebView Android project, not a prebuilt/signed APK. It has not been compiled or tested on a physical Android device in this environment. The underlying HTML features are the V8.1 build; this wrapper does not add missing DSP features or turn browser-based WAV/WebM export into a native MP3 encoder. Test microphone capture, importing, playback and export on the target phone before distributing.
