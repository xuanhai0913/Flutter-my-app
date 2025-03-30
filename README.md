# Flutter Team Members App

This is a simple Flutter app that displays a list of team members using a `PageView`. It supports navigation between members and includes an option to return to the home screen.

## Prerequisites
Before running the application, ensure you have the following installed:

- Flutter SDK (latest stable version)
- Dart SDK
- Android Studio or Visual Studio Code with Flutter extension
- Xcode (for iOS development)
- A physical device or emulator (iOS Simulator or Android Emulator)

## Setup Instructions

### 1. Clone the Repository
```sh
git clone <repository_url>
cd <project_directory>
```

### 2. Install Dependencies
```sh
flutter pub get
```

### 3. Run the App
#### Android
```sh
flutter run
```
Make sure an Android emulator or physical device is connected.

#### iOS
```sh
flutter run
```
Ensure you have an iOS device or the iOS Simulator running.

If running on a physical iOS device, you may need to configure code signing in Xcode:
1. Open `ios/Runner.xcworkspace` in Xcode.
2. Go to **Signing & Capabilities** and select your development team.
3. Run `flutter build ios` before deploying to a real device.

### 4. Build APK for Android
```sh
flutter build apk
```
This will generate an `.apk` file in `build/app/outputs/flutter-apk/`.

### 5. Build iOS App
```sh
flutter build ios
```
For App Store distribution, use:
```sh
flutter build ipa
```

## Troubleshooting
- Run `flutter doctor` to check for any missing dependencies.
- If you encounter permission issues on macOS, try:
  ```sh
  sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
  ```
- For Android, ensure you have an emulator or device connected and debugging enabled.

## License
This project is licensed under the MIT License.

