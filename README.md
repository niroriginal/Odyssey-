# Odyssy

**A lightweight, customizable Android TV launcher built for a clean, remote-friendly home screen.**

Odyssy is a personal Android TV launcher project based on the open-source Luncher project. It keeps the original lightweight Kotlin architecture while giving the project its own name and direction.

## Current features

- Browse and launch installed Android TV apps
- Navigate with a TV remote / D-pad
- Reorder or hide apps
- Customize app tile appearance and alignment
- Choose a wallpaper and adjust its appearance
- Change the launcher’s accent color and light/dark menu theme
- Designed to work on Android TV devices, including Android 12

## Project status

Odyssy is actively being customized. Recently played apps and a curated movie/TV recommendation section are planned next. Recommendations will start with curated content and will not require an API key or account.

## Build

This project uses Gradle and Kotlin. To build a debug APK locally:

```bash
./gradlew assembleDebug
```

The APK is normally produced at:

```
app/build/outputs/apk/debug/app-debug.apk
```

You can also use the repository’s GitHub Actions workflow, when enabled, to build the APK in the cloud.

## Device compatibility

The project targets Android TV-style devices. Odyssy is being developed and tested with a DNA Hub 2.0 running Android 12. As with any launcher, behavior can vary by device manufacturer and system launcher settings.

## Credits

Odyssy is based on [Luncher by CVasilakis](https://github.com/CVasilakis/luncher), an open-source lightweight Android TV launcher. Original project documentation and licensing terms are available in the upstream repository. This repository is a personal fork and is not affiliated with the original author.
