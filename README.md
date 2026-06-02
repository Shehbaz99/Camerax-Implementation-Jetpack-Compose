# 📸 CameraX Implementation with Jetpack Compose

A modern Android application built with **Kotlin**, **Jetpack Compose**, and **CameraX** that demonstrates camera preview, image capture, lifecycle-aware camera management, and modern Android UI development using a declarative approach.

This project was created as a learning-focused implementation to explore Google's recommended camera APIs and gain hands-on experience with modern Android development practices.

---

# 🚀 Features

### 📷 Camera Preview

* Real-time camera preview
* Lifecycle-aware camera handling
* Front and back camera support
* Smooth preview rendering

### 📸 Image Capture

* Capture high-quality photos
* Save images to device storage
* CameraX ImageCapture integration
* Fast capture performance

### 🔄 Camera Switching

* Switch between front and rear cameras
* Dynamic camera binding
* Seamless user experience

### 🎨 Modern UI with Jetpack Compose

* Declarative UI development
* State-driven interface
* Responsive layouts
* Material Design components

### ⚡ Lifecycle-Aware Camera Management

* Automatic camera resource management
* Camera binding to lifecycle owners
* Efficient handling of configuration changes

---

# 📸 Screenshots


---

# 🛠️ Tech Stack

## Language

* Kotlin

## UI Framework

* Jetpack Compose
* Material Design 3

## Camera APIs

* CameraX
* Preview
* ImageCapture
* CameraSelector

## Android Components

* ViewModel
* State Management
* Lifecycle Components

## Asynchronous Programming

* Coroutines

## Architecture

* MVVM

---

# 📂 Project Structure

```text
com.cameraximplementation

├── ui
│   ├── screens
│   ├── components
│   └── theme
│
├── camera
│   ├── preview
│   ├── capture
│   └── selector
│
├── viewmodel
│
├── utils
│
└── navigation
```

---

# 🎯 Core Functionalities

## Camera Preview

The application uses CameraX Preview API to display a real-time camera feed while maintaining compatibility across Android devices.

Features include:

* Live camera stream
* Lifecycle-aware binding
* Optimized camera initialization

---

## Image Capture

Users can capture photos directly from the application using CameraX ImageCapture.

Capabilities include:

* High-quality image capture
* Storage integration
* Capture callbacks
* Error handling

---

## Camera Selection

Allows switching between:

* Front Camera
* Back Camera

using CameraSelector APIs.

---

# 🧠 What I Learned

This project was built primarily to gain hands-on experience with:

* Jetpack Compose
* CameraX APIs
* Android Lifecycle Management
* State Management in Compose
* Camera Resource Handling
* Modern Android Architecture
* Declarative UI Development
* Coroutines
* Runtime Permissions

---

# 🔥 Technical Challenges

## Camera Lifecycle Management

One of the biggest challenges was ensuring camera resources were properly bound and released according to the Activity/Composable lifecycle.

### Solution

Used CameraX lifecycle-aware APIs to automatically manage camera resources and prevent leaks.

---

## Compose + CameraX Integration

Integrating a traditional Android View-based camera preview inside a Compose application required interoperability between Compose and Android Views.

### Solution

Used AndroidView to host PreviewView while keeping the rest of the UI fully Compose-based.

---

## Runtime Permissions

Managing camera permissions gracefully while maintaining a smooth user experience required handling multiple permission states.

### Solution

Implemented permission checks before camera initialization and provided fallback UI when permissions were denied.

---

# 📦 Installation

## Clone Repository

```bash
git clone https://github.com/Shehbaz99/Camerax-Implementation-Jetpack-Compose.git
```

## Open Project

```bash
File → Open → Select Project Folder
```

## Build & Run

```bash
Sync Gradle
Run Application
```

---

# 🔗 Repository

### GitHub

https://github.com/Shehbaz99/Camerax-Implementation-Jetpack-Compose

---

# 🔮 Future Improvements

Planned enhancements include:

* Video Recording
* Flash Control
* Pinch-to-Zoom
* Tap-to-Focus
* Image Filters
* Camera Gallery Preview
* QR Code Scanning
* ML Kit Integration
* Face Detection
* Barcode Recognition

---

# 👨‍💻 Author

## Shehbaz Hussain

Android Developer passionate about modern Android development, Kotlin, Jetpack Compose, Camera APIs, and building scalable mobile applications.

### Connect With Me

* GitHub: https://github.com/Shehbaz99
* LinkedIn: https://linkedin.com/in/shehbazhussain99

---

# ⭐ Support

If you found this project useful, consider giving it a star on GitHub. Feedback and contributions are always welcome.
