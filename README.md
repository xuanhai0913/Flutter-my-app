# 🚀 Flutter Team Members App

This is a simple Flutter application that displays a team member list using `PageView`. The app allows navigation between members and includes an option to return to the home screen.

## 🔧 Requirements
Before running the application, ensure you have installed the following tools:

- 🏗️ Flutter SDK (latest stable version)
- 📝 Dart SDK
- 🖥️ Android Studio or Visual Studio Code with Flutter extension
- 🍏 Xcode (for iOS development)
- 📱 A physical device or an emulator (iOS Simulator or Android Emulator)

## 📥 Installation Guide

### 1️⃣ Clone the repository
```sh
git clone https://github.com/xuanhai0913/Flutter-my-app.git
cd Flutter-my-app
```

### 2️⃣ Install dependencies
```sh
flutter pub get
```

### 3️⃣ Run the application
#### 🤖 Android
```sh
flutter run
```
Make sure a physical Android device is connected or an emulator is running.

#### 🍏 iOS
```sh
flutter run
```
Make sure a physical iOS device is connected or the iOS Simulator is running.

If running on a real iOS device, configure code signing in Xcode:
1. Open `ios/Runner.xcworkspace` in Xcode.
2. Navigate to **Signing & Capabilities** and select your development team.
3. Run `flutter build ios` before deploying to a real device.

### 📦 Build APK for Android
```sh
flutter build apk
```
The `.apk` file will be generated in `build/app/outputs/flutter-apk/`.

### 🍏 Build iOS App
```sh
flutter build ios
```
To publish to the App Store, use:
```sh
flutter build ipa
```

## 🛠️ Troubleshooting
- Run `flutter doctor` to check for any missing dependencies.
- If encountering permission issues on macOS, try running:
  ```sh
  sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
  ```
- For Android, ensure the device or emulator is properly connected and debugging mode is enabled.

## 🔗 GitHub Repository
You can view the project's source code at: [Flutter-my-app](https://github.com/xuanhai0913/Flutter-my-app)

## 📜 License
This project is licensed under the MIT License.

