# UI Design App

A simple Android application built with **Kotlin** and **Jetpack Compose** to demonstrate modern Android UI development concepts including navigation, state management, Material 3 components, and responsive layouts.

## Features

* User input form using `OutlinedTextField`
* Navigation between screens using Navigation Compose
* Responsive dashboard built with `LazyVerticalGrid`
* Material 3 design components
* Adaptive grid layout that adjusts to different screen sizes
* Back navigation support

## Technologies Used

* Kotlin
* Jetpack Compose
* Material 3
* Navigation Compose

## Project Structure

```text
MainActivity.kt
README.md
```

The `MainActivity.kt` file contains:

* Application entry point (`MainActivity`)
* Navigation setup using `NavHost`
* Route management using a sealed class
* Form screen implementation
* Dashboard screen implementation

## Key Concepts Demonstrated

* Declarative UI development with Jetpack Compose
* State management using `remember` and `mutableStateOf`
* Navigation with `NavController`
* Responsive layouts using `GridCells.Adaptive`
* Material 3 components and theming

## Dependencies

Add the following dependency to your `app/build.gradle.kts` file:

```gradle
implementation("androidx.navigation:navigation-compose:2.8.5")
```

Ensure AndroidX is enabled in `gradle.properties`:

```properties
android.useAndroidX=true
android.enableJetifier=true
```

## How to Run

1. Create a new **Empty Activity** project in Android Studio with Jetpack Compose enabled.
2. Replace the generated `MainActivity.kt` file with the source code provided in this repository.
3. Add the Navigation Compose dependency to `app/build.gradle.kts`.
4. Sync the Gradle project.
5. Run the application on an Android emulator or physical device.

## Learning Outcomes

This project demonstrates practical usage of:

* Jetpack Compose fundamentals
* Screen navigation
* State handling
* Responsive UI design
* Material 3 design principles

---

Created as a learning project to explore modern Android development using Kotlin and Jetpack Compose.
