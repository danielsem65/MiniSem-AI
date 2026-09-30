# Building MiniCPM Android

## Development Environment Setup

### 1. Install Required Tools

- Android Studio 2022.1 or later
- Android NDK (r23 or later)
- JDK 11 or later
- CMake 3.22.1 or later

### 2. Clone and Setup

```bash
git clone https://github.com/danielsem65/MiniSem-AI.git
cd MiniSem-AI/MiniCPM-Android
```

### 3. Configure NDK Path

Create or modify `local.properties` in the project root:

```properties
sdk.dir=/path/to/android/sdk
ndk.dir=/path/to/android/ndk
```

### 4. Build

```bash
./gradlew build
```

## Troubleshooting

- If NDK is not found, ensure `ndk.dir` is correctly set in `local.properties`
- Clean build cache if issues persist: `./gradlew clean build`

## Running

Connect an Android device and run:

```bash
./gradlew installDebug
```
