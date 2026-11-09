# Task Manager UI

A single "All tasks completed / Nice work!" screen with a checkmark illustration.

Built while following Google's [Android Basics with Compose](https://developer.android.com/courses/android-basics-compose/course) course (the "Task manager" practice problem).

## Features

- Centered image, bold headline and subtext from string resources

## Built with

- Kotlin, Jetpack Compose, Material 3
- Small reusable composables (`BackgroundImage`, `MainText`, `SubText`)
- Min SDK 24, target/compile SDK 35

## Run it

1. Open the project folder in Android Studio and let Gradle sync.
2. Run the `app` configuration on an emulator or device (Android 7.0 / API 24 or newer).

Or, with a device or emulator connected:

```sh
./gradlew installDebug
```
