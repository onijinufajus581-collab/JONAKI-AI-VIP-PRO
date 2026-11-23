# JONAKI AI VIP v2
Upload all files/folders in this project to the root of your GitHub repository. Keep the hidden `.github/workflows/android.yml` path.
Open Actions, run/wait for **Build JONAKI AI VIP APK**, then download the `JONAKI-AI-VIP-APK` artifact and extract `app-debug.apk`.

This is a Java-only APK with no native ABI-specific libraries. It includes launcher icon resources for modern and older Android versions. Microphone permission is requested only after tapping Listen.

Voice recognition depends on the speech service installed on the phone and may need internet. Bengali and feminine-sounding TTS depends on voices available in Android Text-to-Speech settings; the app cannot guarantee a female voice if none is installed.

This version has working built-in voice commands for time, YouTube, Facebook, Telegram, Play Store and greetings. It is not a full general-purpose AI model. Full AI conversation requires an AI service/API. Listening works while the app is open; it does not secretly listen in the background.
