# BHU Student Cafeteria System (Android App) 📱

This is the official Android application for the **BHU Student Cafeteria System**. It provides a native mobile experience by wrapping the core web application in a highly optimized Android `WebView`.

The primary goal of this app is to provide cafeteria operators with a dedicated, easy-to-distribute, and reliable tool that works seamlessly on their Android devices, ensuring all features of the web system are accessible in a familiar app format.

---

## 🌟 About The Developer

This project was developed by **Biruk Tadesse**, a Computer Science and Engineering (CSE) student with a passion for creating impactful software solutions. This Android wrapper is a demonstration of my skills in mobile development and my ability to integrate web technologies into a native mobile environment.

> My focus is on delivering complete, end-to-end solutions. While the core logic of this system resides in the web application, creating this native Android shell showcases my versatility and understanding of the mobile ecosystem, from project setup in Android Studio to generating a distributable, signed APK.

---

## ✨ Core Features

This Android app inherits all the powerful features of the core web application, including:

-   **🚀 Real-time, Multi-User Synchronization** via Firebase Firestore.
-   **🔌 100% Offline-First Capability** with automatic data syncing.
-   **🌍 Full Multi-Language Support** (English, Afaan Oromoo, Amharic).
-   **🎨 Modern UI/UX** with Dark Mode and responsive design.
-   **🔊 Sound and Vibration Feedback** for critical user actions.

In addition, the Android version offers:
-   **Dedicated App Experience:** No need to open a browser; the system is always one tap away.
-   **Full Screen Immersion:** The app hides the browser UI for a clean, focused interface.
-   **Easy Distribution:** The generated `.apk` file can be easily shared among operators via Xender, Bluetooth, or other file-sharing methods.

---

## 📸 Screenshots

*(Asitti, suuraawwan appilikeeshinichaa bilbila irratti yeroo hojjetu agarsiisan kaa'i)*

| Welcome Screen | Session Selection |
| :---: | :---: |
| ![App Welcome]([YOUR_APP_SCREENSHOT_URL_1]) | ![App Session]([YOUR_APP_SCREENSHOT_URL_2]) |

| Main Entry Screen (Dark Mode) | Side Menu |
| :---: | :---: |
| ![App Main Dark]([YOUR_APP_SCREENSHOT_URL_3]) | ![App Side Menu]([YOUR_APP_SCREENSHOT_URL_4]) |

---

## 🛠️ Technology Stack

-   **Core Platform:** Android (Java)
-   **Rendering Engine:** Android `WebView`
-   **Web Technologies:** The app renders the web project built with HTML5, CSS3, and Vanilla JavaScript.
-   **Development Environment:** Android Studio
-   **Version Control:** Git & GitHub

---

## 🚀 How to Build and Run

Follow these steps to build the Android application from the source code.

1.  **Prerequisites:**
    -   [Android Studio](https://developer.android.com/studio) (latest stable version recommended).
    -   An Android device or emulator running API 24 or higher.

2.  **Clone the Repository:**
    ```sh
    git clone https://github.com/birru2217/bhu-cafeteria-android-app.git
    ```

3.  **Open in Android Studio:**
    -   Launch Android Studio.
    -   Select **"Open an existing Project"** and navigate to the cloned `bhu-cafeteria-android-app` folder.

4.  **Sync Gradle:**
    -   Allow Android Studio a few minutes to sync the project and download the required Gradle dependencies.

5.  **Generate a Signed APK for Distribution:**
    -   Go to **Build > Generate Signed Bundle / APK...**.
    -   Select **APK**.
    -   Choose your `keystore` (or create a new one).
    -   Select the **`release`** build variant.
    -   Click **Finish**.
    -   The final, shareable `app-release.apk` will be located in the `app/release` folder.

---

## 🔗 Related Project: The Core Web Application

This Android app is a wrapper for the core web project. All the client-side logic and UI are managed in the web repository.

➡️ **[View the Web Application Repository Here](https://github.com/birru2217/bhu-cafeteria-website)**

---
