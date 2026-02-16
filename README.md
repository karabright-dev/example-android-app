# Counter App

A simple Android counter application demonstrating basic Android development with Java.

## Features

- Increment counter with + button
- Decrement counter with - button  
- Reset counter to 0
- Clean Material Design 3 interface
- Responsive layout using ConstraintLayout

## Download

You can download the pre-built APK here: **[app-debug.apk](app-debug.apk)**

## Building from Source

### Prerequisites
- Java 17 (OpenJDK)
- Android SDK with API 34
- Gradle 8.5+

### Build Instructions

To build the debug APK:
```bash
./gradlew assembleDebug
```

The APK will be located at:
`app/build/outputs/apk/debug/app-debug.apk`

## App Structure

- **MainActivity.java** - Main activity with counter logic
- **activity_main.xml** - Layout with counter display and buttons
- Uses AndroidX and Material Design 3 components

## Screenshots

The app features:
- Large counter display (72sp text)
- Three action buttons: [-] [Reset] [+]
- Purple accent color theme
- Clean, centered layout