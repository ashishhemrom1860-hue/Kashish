# Kashish Advanced Android Voice Assistant

This version adds Hindi + English voice commands and an optional foreground wake-word mode.

## Added features
- Hindi + English speech recognition (hi-IN)
- "Hey Kashish" / "काशिश" wake mode using a microphone foreground service
- Home, Back, Recents, Notifications, Quick Settings, Lock
- Open common apps and search installed apps by spoken name
- Dial a spoken phone number
- SMS composer with spoken number/message
- WhatsApp composer with spoken number/message
- Music Play/Pause/Next/Previous
- Volume up/down/mute/unmute
- Brightness by percentage (requires Android Write Settings permission)
- Screenshot to Pictures/Kashish (Android 11+ and Accessibility)
- Flashlight on/off
- Scroll up/down
- Text-to-speech responses

## Setup
1. Build/install the APK.
2. Grant Microphone and Notifications permissions.
3. Enable Kashish in Android Settings > Accessibility.
4. For brightness, grant "Modify system settings" to Kashish.
5. Tap "Hey Kashish Wake Mode ON" to start wake mode.

## Example commands
- Hey Kashish, open YouTube
- Hey Kashish, call 9876543210
- Hey Kashish, SMS 9876543210 hello how are you
- Hey Kashish, WhatsApp 9876543210 hello
- Hey Kashish, play music
- Hey Kashish, next song
- Hey Kashish, brightness 50 percent
- Hey Kashish, screenshot
- Hey Kashish, torch on
- Hey Kashish, scroll down

## Android limitations
A normal third-party app cannot silently control everything on Android. Some actions are intentionally routed to system UI/composers (dialer, SMS, WhatsApp) instead of sending automatically. Always-on wake-word recognition depends on Android microphone/foreground-service rules and battery optimization, so it is not guaranteed to remain active indefinitely.
