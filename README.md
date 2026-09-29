# Kashish AI - Android starter v2

A starter Android voice assistant with tap-to-speak Hindi/English recognition, text-to-speech, quick commands for YouTube/browser, dialer, SMS composer, Google search, date/time, battery level, and Android Settings.

Notes:
- This is not a full AI assistant yet; no AI API is configured.
- Wake-word detection ("Hey Kashish" while the app is closed/backgrounded) is not included.
- Calls and SMS open the Android confirmation/composer UI; the app does not silently place calls or send messages.
- Requires Android SDK 35 and Java 17 to build. GitHub Actions workflow builds a debug APK.
