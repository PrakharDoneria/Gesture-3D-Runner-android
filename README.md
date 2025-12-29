
# Gesture 3D Runner - Android Project

This project was exported from Karbon Sites and is ready to be built as an Android application using Capacitor.

## Prerequisites

1.  **Node.js and npm**: Make sure you have Node.js (which includes npm) installed.
2.  **Java Development Kit (JDK)**: You'll need a recent version of the JDK (e.g., OpenJDK 17).
3.  **Android Studio**: Download and install the latest version of Android Studio. Make sure to set up the Android SDK.

## Build Steps

1.  **Unzip the Project**: Unzip this file into a new folder on your computer.

2.  **Open a Terminal**: Navigate into the project folder using your terminal or command prompt.
    ```bash
    cd /path/to/your/unzipped-project
    ```

3.  **Install Dependencies**: Run the following command to install Capacitor and its dependencies.
    ```bash
    npm init -y
    npm install @capacitor/core @capacitor/cli @capacitor/android typescript
    ```

4.  **Add the Android Platform**: This command creates the native Android project.
    ```bash
    npx cap add android
    ```

5.  **Open in Android Studio**: Open the native project in Android Studio.
    ```bash
    npx cap open android
    ```

6.  **Build the APK**:
    *   Once Android Studio opens and finishes syncing, go to the **Build** menu.
    *   Select **Build Bundle(s) / APK(s)** > **Build APK(s)**.
    *   After the build is complete, you will see a notification. Click "locate" to find your generated `.apk` file in the `app/build/outputs/apk/debug` directory.

That's it! You can now install this APK on an Android device for testing.
    