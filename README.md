# Compose Article

A simple Jetpack Compose Android application that demonstrates how to build a basic UI layout using Compose.

## 📱 About This Project

This project is a beginner-friendly Android application built with **Jetpack Compose**. It displays a simple article layout consisting of:
- A header image.
- An article title.
- A short description paragraph (justified text).
- A longer descriptive paragraph (justified text).

It showcases the use of core Jetpack Compose UI elements, including `Column`, `Image`, `Text`, and `Modifier` for padding and text alignment.

## 🛠️ Built With

* [Kotlin](https://kotlinlang.org/) - First-class and official programming language for Android development.
* [Jetpack Compose](https://developer.android.com/jetpack/compose) - Android's modern toolkit for building native UI.
* [Material Design 3](https://m3.material.io/) - Modern styling and theming.

## 🚀 Getting Started

To open and run this project:

1. Clone this repository or download the project files.
2. Open **Android Studio** (Koala or newer is recommended).
3. Select **File > Open...** and navigate to the project directory (`ComposeArticle`).
4. Let Gradle sync and build the project.
5. Click the **Run** button to launch the app on an emulator or physical Android device.

## 📂 Project Structure

- `MainActivity.kt`: Contains the entry point and the declarative Jetpack Compose UI (`ComposeArticleApp` and `ArticleCard` composables).
- `ui.theme`: Contains the Material 3 typography, colors, and theme configurations used in the app.
- `res`: Contains the string resources (`strings.xml`) and drawable resources used for the article.
