# Flutter Meals App

A cross-platform Flutter application for browsing and managing meals, built with [Flutter](https://flutter.dev/) and [Riverpod](https://riverpod.dev/).

> **Note:** This project is part of the [A Complete Guide to the Flutter SDK & Flutter Framework for building native iOS and Android apps](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/) course on Udemy.

## Features

- Browse a variety of meals
- Material 3 design with custom theming
- State management using Riverpod
- Uses Google Fonts for enhanced typography

## Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- [Dart SDK](https://dart.dev/get-dart) (usually included with Flutter)
- An IDE such as [VS Code](https://code.visualstudio.com/) or [Android Studio](https://developer.android.com/studio)

### Installation

1. **Clone the repository:**

   ```sh
   git clone <repository-url>
   cd flutter_meals_app
   ```

2. **Install dependencies:**

   ```sh
   flutter pub get
   ```

3. **Run the app:**
   - For mobile:
     ```sh
     flutter run
     ```
   - For web:
     ```sh
     flutter run -d chrome
     ```
   - For desktop (macOS, Windows, Linux):
     ```sh
     flutter run -d <platform>
     ```

## Project Structure

- `lib` - Main Dart source code
- `android`, `ios`, `macos`, `linux`, `windows`, `web` - Platform-specific code
- `test` - Unit and widget tests

## License

This project is licensed under the terms described in the `LICENSE` file.

---

For more information, see the [Flutter documentation](https://docs.flutter.dev/).
