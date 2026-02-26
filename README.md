# 📌 Business Card App (Jetpack Compose)

## 📖 Project Overview
This project is a simple **Business Card Application** built using **Jetpack Compose** in Android Studio.  
The app displays a developer business card layout that adapts to:

- 📱 Phone (Portrait Mode)
- 💻 Tablet / Landscape Mode

The UI is created using Compose components like `Column`, `Row`, `Text`, and `Modifier` with responsive behavior based on screen orientation.

---

## 🛠 Tech Stack
- **Language:** Kotlin  
- **UI Toolkit:** Jetpack Compose  
- **Minimum SDK:** 24  
- **Target SDK:** 35  
- **Compile SDK:** 35  
- **Android Gradle Plugin:** 8.7.3  
- **Gradle Version:** 8.9  

---

## 🎯 Features
- ✅ Responsive layout (Portrait & Landscape)
- ✅ Clean Material 3 design
- ✅ Proper spacing using Modifier
- ✅ Organized composable structure
- ✅ Orientation detection using `LocalConfiguration`

---
## 📐 Layout Design Logic

### 📱 Portrait Mode
- Uses `Column`
- Content centered vertically
- Name displayed in large bold font
- Role below the name
- Contact details at the bottom

### 💻 Landscape Mode
- Uses `Row`
- Horizontal alignment
- Better width utilization
- Slightly larger text for readability

---

## ▶️ How to Run
1. Open the project in Android Studio.
2. Sync Gradle files.
3. Run the app on an emulator or physical device.
4. Rotate the device to view landscape layout.

---

# 📸 Output Screenshots

## 1️⃣ Phone – Portrait Mode
Displays:
- Name: Rani Kini  
- Role: Android Developer  
- Phone & Email  
- Centered vertical layout  

<p align="center">
  <img src="app_output.jpeg" width="250">
</p>


