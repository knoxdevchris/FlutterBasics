# Flutter Basics Tutorial

This repository contains a small Flutter project that demonstrates common widgets and structure.
It can be used as a starting point for learning Flutter.

## Getting Started

1. **Install Flutter** – Follow the [official installation guide](https://docs.flutter.dev/get-started/install) for your platform.
2. **Clone this repository**
   ```bash
   git clone <repo-url>
   cd FlutterBasics
   ```
3. **Run Flutter Doctor** – Ensure your environment is ready.
   ```bash
   flutter doctor
   ```
4. **Get the dependencies**
   ```bash
   flutter pub get
   ```
5. **Run the app**
   ```bash
   flutter run
   ```

## What does this example show?

The app displays a counter with a button to increment it. It demonstrates:

- `MaterialApp` setup.
- A `StatefulWidget` (`MyHomePage`).
- Using `setState` to update UI when the button is pressed.
- Basic layout widgets (`Scaffold`, `AppBar`, `Center`, `Column`).

You can modify `lib/main.dart` to experiment with your own widgets and layouts.

## Directory Structure

```
FlutterBasics/
├── lib/
│   └── main.dart
├── pubspec.yaml
└── README.md
```

This is intentionally simple so new Flutter developers can focus on the core concepts.
