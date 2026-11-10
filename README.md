# DES3113 - Colour Mix

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter)](https://flutter.dev/)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart)](https://dart.dev/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 📖 Project Overview
**Colour Mix** is an interactive mobile application developed as part of the **DES3113 Mobile Application Development** coursework. The app allows users to dynamically adjust Red, Green, and Blue (RGB) color channels via intuitive sliders and observe instant, real-time color synthesis inside a custom circular canvas preview.

---

## ✨ Key Features
* **Real-time Color Synthesis**: Adjust individual RGB channels (0–255) with instantaneous color output updates.
* **Modular Widget Architecture**:
  * `ColorCircle`: Reusable custom widget dedicated to rendering the mixed color preview with configurable dimensions.
  * `ColorValueChanger`: Modular slider component encapsulating label, current channel intensity, and dynamic color styling.
* **State Management**: Implements clean Flutter `StatefulWidget` reactive state management using `setState`.
* **Cross-Platform Compatibility**: Fully compatible with Android, iOS, Web, and Desktop environments.

---

## 🛠 Tech Stack
* **Framework:** Flutter (Material Design)
* **Language:** Dart
* **Architecture:** Modular Component Pattern

---

## 📂 Directory Structure
```text
lib/
├── color_circle.dart         # Custom widget for rendering the synthesized color preview
├── color_value_changer.dart  # Custom slider widget for individual RGB channel control
└── main.dart                 # Application entrypoint & state management logic
```

---

## 🚀 Getting Started

### Prerequisites
* [Flutter SDK](https://docs.flutter.dev/get-started/install) (v3.0.0 or higher)
* Android Studio / VS Code with Flutter extension
* An active emulator or physical device

### Installation & Run
```bash
# 1. Clone the repository
git clone https://github.com/Wong0813/DES3113-ColourMix.git
cd DES3113-ColourMix

# 2. Get dependencies
flutter pub get

# 3. Launch application
flutter run
```
