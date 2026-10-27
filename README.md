# Android Activity Lifecycle & Multi-Activity Task

This repository contains a simple Android application demonstrating the **Android Activity Lifecycle** and explicit intents for navigating between multiple activities, built as part of a mobile application development assignment.

---

## 📂 Project Structure

The project follows standard Android project architecture:

* **`AndroidManifest.xml`**: Registers both activities and defines the application components and launcher intent.
* **`MainActivity.java`**: The entry point activity containing lifecycle state logging (`Log.d`) and a button to launch the secondary activity.
* **`SecondActivity.java`**: The secondary activity demonstrating multi-activity transitions and lifecycle state tracking.
* **`activity_main.xml`**: The user interface layout for the main screen.
* **`activity_second.xml`**: The user interface layout for the second screen.

---

## 🚀 Features Demonstrated

1. **Activity Lifecycle Callbacks**: 
   * Traces and logs state changes (`onCreate`, `onStart`, `onResume`, `onPause`, `onStop`, `onRestart`, `onDestroy`) in **Logcat**.
2. **Explicit Intents**:
   * Navigating from `MainActivity` to `SecondActivity` using `Intent`.
   * Returning from `SecondActivity` to `MainActivity` using `finish()`.

---
