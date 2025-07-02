# 🏌️ Blade — AI-Powered Golf Swing & Putting Analysis App

**Blade** is a personal performance tool designed to help golfers improve their game using real-time swing analysis, GPS shot tracking, putting performance insights, and AI-powered feedback — all in a sleek, mobile-first Flutter app.

---

## 🚀 Features

- 📸 **Swing Capture** – Upload or record your golf swing directly from your phone.
- 🧠 **Pose Estimation with TFLite** – Detect body landmarks using MoveNet SinglePose Lightning.
- 📊 **Swing Feedback** – Analyze tempo, club path, hip rotation, and more.
- 📏 **FitFinder** – Personalized recommendations for club length, ball type, and equipment.
- 📍 **GPS Shot Tracker** – Real-time shot distance tracking with wind/slope adjustments.
- ⛳ **Putting Tracker** – Visualize make/miss zones and performance trends over time.
- ☁️ **Firebase Integration** – Store swing results, stats, and video data securely in the cloud.
- 🔒 **Permissions** – Smart initialization of location, camera, and storage services.

---

## 🧱 Project Structure

lib/
├── main.dart
├── screens/
│ ├── swing_capture.dart
│ ├── swing_results.dart
│ ├── putting_tracker.dart
│ ├── putting_stats_dashboard.dart
│ ├── navigation_wrapper.dart
│ ├── settings.dart
│ └── ...
assets/
└── models/
└── movenet_singlepose_lightning.tflite


---

## 🔧 Getting Started

### Prerequisites
- Flutter SDK ≥ 3.0
- Firebase Project (Firestore, Storage, Auth)
- Android Studio / Xcode / VS Code
- `google-services.json` for Android or `GoogleService-Info.plist` for iOS

### Installation
```bash
git clone https://github.com/YOUR_USERNAME/blade_app.git
cd blade_app
flutter pub get
flutter run
