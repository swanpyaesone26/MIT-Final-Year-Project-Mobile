# CEO Assist

A Flutter-based cross-platform mobile application for the CEO Assist project. This app provides a mobile interface to interact with the Django backend, enabling seamless functionality across iOS, Android, and web platforms.

## Features

- Cross-platform support (iOS, Android, Web)
- Seamless integration with Django backend
- Native performance with Flutter

## Prerequisites

- Flutter 3.0 or higher
- Dart SDK
- Android Studio (for Android development)
- Xcode (for iOS development)

## Getting Started

1. Clone the repository
2. Run `flutter pub get` to install dependencies
3. Update the backend API endpoint in the configuration
4. Run `flutter run` to launch on your connected device/emulator

## Project Structure

```
lib/              - Dart application code
android/          - Android-specific configuration
ios/              - iOS-specific configuration
web/              - Web platform files
test/             - Widget tests
```

## Building

- **Android**: `flutter build apk` or `flutter build appbundle`
- **iOS**: `flutter build ios`
- **Web**: `flutter build web`

## Backend

This project requires the Django backend to be running. Ensure the backend API is properly configured in the app settings.
