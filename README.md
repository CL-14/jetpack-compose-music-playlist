# Android Jetpack Compose Music Playlist App

A modern, feature-rich Android mobile application built with **Jetpack Compose** and **Kotlin** following the **MVVM (Model-View-ViewModel)** architectural pattern. The app showcases a curated playlist of tracks from *Xenoblade Chronicles*, complete with interactive state management and navigation.

## Key Features & Architecture
* **Declarative UI (Jetpack Compose):** Utilizes material components, smooth animations, lazy columns, and custom styling.
* **MVVM Architecture:** Separates business logic and state (`SongViewModel`) from the presentation layer (`PlaylistScreen`, `SongDetailScreen`).
* **Navigation Components:** Uses Jetpack Navigation (`NavHost`) to handle seamless screen transitions and pass parameters (song IDs) to detail views.
* **Interactive List Management:** 
  * Add new songs with built-in client-side input validation and error handling.
  * Delete items with animated removal tracking.
  * Toggle favorite status dynamically with instant UI updates.

## Tech & Libraries
* **Language:** Kotlin
* **UI Framework:** Jetpack Compose (Material 3)
* **Architecture:** ViewModel, State Management (`mutableStateListOf`)
* **Routing:** Jetpack Navigation Compose
