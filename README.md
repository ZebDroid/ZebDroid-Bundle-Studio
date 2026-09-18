# ZebDroid Bundle Studio

A desktop toolkit for analyzing, inspecting, modifying, validating, and testing Android App Bundles (`.aab`).

Built with **Java (Swing)** by **Zuhaib**.

## Features

### 📦 AAB Analyzer
Analyze any `.aab` file and get a detailed breakdown of:

- Manifest
- Modules
- Resources
- Bundle structure

### 🏷️ App & Package Name Editor
Change the application **Label (App Name)** and **Package Name** directly inside an existing App Bundle.

### 🎯 Target SDK Editor
Change the Target SDK version of an existing bundle without rebuilding the application from source.

### ✍️ AAB Signer
Sign an App Bundle using your own keystore.

### ✅ AAB Validator
Perform structural and Play Store readiness checks before publishing.

### 🔍 AAB Inspector
Deep-dive into the internal contents and structure of an Android App Bundle.

### 🔬 AAB Compare
Compare two `.aab` files and identify differences between their contents.

### 🚀 Play Preflight
Run pre-upload checks designed to help identify potential Google Play Console issues before submission.

### 📱 Universal APK Builder
Generate a Universal APK from an App Bundle for quick sideload testing.

### 🖥️ Guided Desktop GUI
A clean Java Swing interface where you select a bundle once and access relevant actions such as:

- Edit
- Inspect
- Validate
- Preflight
- Compare
- Build APK

No need to remember CLI menu numbers.

### ⚙️ CLI-Powered GUI
The GUI is a frontend for the real CLI engine. Results displayed by the GUI come directly from the underlying CLI tools.

## Technology

- Java
- Java Swing
- Android App Bundle (`.aab`)
- Bundletool
- CLI-based processing

## Author

**Zuhaib**

Built with ❤️ by ZebDroid.
