# Odyssey

**A lightweight, customizable Android TV launcher with a cinematic, remote-friendly home screen.**

Odyssey is a personal Android TV launcher project based on the open-source [Luncher](https://github.com/CVasilakis/luncher) project. The original lightweight Kotlin architecture remains in place while the app and project documentation use the Odyssey name.

## Features

- Launch installed Android TV apps using the TV remote / D-pad
- Recently played apps, saved locally on the device
- Curated movie and TV picks; select a title to search the web for streaming availability
- No recommendation API key, account, or background tracking service required
- Reorder or hide apps
- Customize app tile appearance and alignment
- Choose a wallpaper and adjust its appearance
- Change the accent color and light/dark menu theme
- Designed for Android TV devices, including the DNA Hub 2.0 running Android 12

## Recommendations and privacy

The initial recommendations are a built-in curated list, not live or personalized streaming-service data. Selecting a recommendation opens a web search; streaming availability depends on region and subscription. Recently played app history stays in local app preferences and is not uploaded.

## Build

With the repository checked out and a JDK/Android build environment installed:

```bash
./gradlew assembleDebug
```

The debug APK is normally produced at `app/build/outputs/apk/debug/app-debug.apk`. GitHub Actions can also build the project when its workflow is enabled.

## Device compatibility

Odyssey is being developed with a DNA Hub 2.0 running Android 12. Launcher behavior can vary by manufacturer and by the device's system launcher settings.

## Credits and licensing

Odyssey is based on [Luncher by CVasilakis](https://github.com/CVasilakis/luncher). See the upstream repository for the original project's license and attribution. This personal fork is not affiliated with the original author.
