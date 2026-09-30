# MiniCPM Android

A lightweight Android implementation of MiniCPM, a small yet powerful language model.

## Features

- Local LLM inference on Android devices
- Support for ARM64 architecture
- JNI integration for native performance
- Material Design UI

## Building

### Prerequisites

- Android Studio 2022.1 or later
- Android NDK r23 or later
- JDK 11 or later
- Gradle 8.0 or later

### Build Steps

1. Clone the repository
2. Open the project in Android Studio
3. Build the project using Gradle:
   ```bash
   ./gradlew build
   ```

## Architecture

- `app/` - Main Android application
- `app/src/main/java/` - Kotlin/Java source code
- `app/src/main/cpp/` - Native C++ code
- `app/src/main/res/` - Android resources

## License

MIT License
