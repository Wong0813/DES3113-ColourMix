# DES3113 - Colour Mix / 动态RGB调色器

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter)](https://flutter.dev/)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart)](https://dart.dev/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

[English](#english) | [中文说明](#chinese)

---

<a name="english"></a>
## 🌐 English

### Project Overview
**Colour Mix** is an interactive mobile application developed as part of the **DES3113 Mobile Application Development** coursework. The app allows users to dynamically adjust Red, Green, and Blue (RGB) color channels via intuitive sliders and observe instant, real-time color synthesis inside a custom circular canvas preview.

### Key Features
* **Real-time Color Synthesis**: Adjust individual RGB channels (0–255) with instantaneous color output updates.
* **Modular Widget Architecture**:
  * `ColorCircle`: Reusable custom widget dedicated to rendering the mixed color preview with configurable dimensions.
  * `ColorValueChanger`: Modular slider component encapsulating label, current channel intensity, and dynamic color styling.
* **State Management**: Implements clean Flutter `StatefulWidget` reactive state management using `setState`.
* **Cross-Platform Compatibility**: Fully compatible with Android, iOS, Web, and Desktop environments.

### Tech Stack
* **Framework:** Flutter (Material Design)
* **Language:** Dart
* **Architecture:** Modular Component Pattern

### Directory Structure
```text
lib/
├── color_circle.dart         # Custom widget for rendering the synthesized color preview
├── color_value_changer.dart  # Custom slider widget for individual RGB channel control
└── main.dart                 # Application entrypoint & state management logic
```

### Getting Started

#### Prerequisites
* [Flutter SDK](https://docs.flutter.dev/get-started/install) (v3.0.0 or higher)
* Android Studio / VS Code with Flutter extension
* An active emulator or physical device

#### Installation & Run
```bash
# 1. Clone the repository
git clone https://github.com/Wong0813/DES3113-ColourMix.git
cd DES3113-ColourMix

# 2. Get dependencies
flutter pub get

# 3. Launch application
flutter run
```

---

<a name="chinese"></a>
## 🇨🇳 中文说明

### 项目简介
**Colour Mix（调色器）** 是在 **DES3113 移动应用开发（Mobile Application Development）** 课程中开发的一个交互式调色移动应用。用户可以通过调节红（Red）、绿（Green）、蓝（Blue）三原色滑动条，实时合成并预览对应的 RGB 混合色彩。

### 核心特性
* **实时色彩混合**：支持独立调节 R、G、B 通道（数值范围 0-255），混色结果实时渲染。
* **组件化封装设计**：
  * `ColorCircle`：自定义圆形画布组件，封装尺寸与混色展示。
  * `ColorValueChanger`：封装标签、滑动条、数值状态与主题色配置，具备高复用性。
* **响应式状态管理**：基于 Flutter `StatefulWidget` 与 `setState` 实现轻量级且精准的响应式数据驱动。
* **多平台支持**：原生支持 Android、iOS、Web 以及桌面端运行。

### 技术栈
* **开发框架：** Flutter (Material Design 3)
* **编程语言：** Dart
* **设计模式：** 自定义可复用组件化架构

### 运行指南
```bash
# 获取依赖
flutter pub get

# 启动运行
flutter run
```
