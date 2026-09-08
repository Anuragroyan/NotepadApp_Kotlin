📝 Notepad App

Notepad App is a modern Android note-taking application that allows users to create, read, update, and delete notes with ease. Built with Kotlin and Jetpack Compose, it supports color-coded notes using customizable Hex colors, making information more organized, visually accessible, and easy to manage.

🎯 Why This Project?

Notepad App was built to demonstrate the implementation of a practical CRUD-based Android application with a clean and modern user interface.

The project focuses on note management, color customization, Firebase data handling, Kotlin Coroutines, and Jetpack Compose UI development.

🚀 Features

* ➕ Create new notes
* 📖 Read and view saved notes
* ✏️ Update existing notes
* 🗑️ Delete notes
* 🎨 Customize note colors
* 🔢 Support Hex color codes
* 🗂️ Organize notes visually using colors
* ☁️ Firebase-based data management
* ⚡ Asynchronous operations using Kotlin Coroutines
* 📱 Modern Jetpack Compose UI
* 🔄 Reactive UI state management

🔄 Application Workflow

Open App → Create Note → Enter Title & Content → Select Hex Color → Save Note → View Notes → Edit / Delete Note

🧩 Main Modules

📝 Note Management

Users can manage their notes through complete CRUD operations:

Create → Read → Update → Delete

Each note can contain:

* Note title
* Note content
* Custom Hex color
* Note information

🎨 Color Customization

Users can assign a custom Hex color to their notes.

Example:

#FF5733 → Orange/Red Note

#3498DB → Blue Note

#2ECC71 → Green Note

This makes different categories of information easier to identify visually.

📋 Notes List

The notes screen displays saved notes in a clean layout, with each note visually distinguished using its selected color.

🏗️ Architecture

Jetpack Compose UI → ViewModel → Repository → Firebase Firestore

Architecture Components

* Jetpack Compose — Modern Android UI
* ViewModel — UI state and business logic
* Repository — Data access abstraction
* Firebase Firestore — Cloud-based note storage
* Kotlin Coroutines — Asynchronous database operations

🛠️ Tech Stack

Kotlin • Jetpack Compose • Android SDK • Firebase Firestore • Kotlin Coroutines • MVVM • CRUD Operations • State Management

📂 Project Structure

Notepad/ → app/ → src/main/ → java/... → ui/ • screens/ • components/ • viewmodel/ • repository/ • model/ → res/ • AndroidManifest.xml → google-services.json → build.gradle.kts → README.md

⚙️ Getting Started

1. Clone the Repository

git clone <repository-url>
cd Notepad

2. Configure Firebase

Create/configure a Firebase project and add:

google-services.json

Place the file inside:

app/google-services.json

Enable:

* Cloud Firestore
* Required Firebase services used by the project

3. Build the Project

./gradlew build

4. Run on Android

./gradlew installDebug

Or open the project in Android Studio and run it on an emulator or physical Android device.

🔄 Data Flow

User Action → Compose UI → ViewModel → Repository → Firebase Firestore → Updated Note Data → Compose UI

🔒 Data Management

* Notes are stored using Firebase Firestore.
* CRUD operations are handled through the repository layer.
* Kotlin Coroutines manage asynchronous database operations.
* UI state is managed through ViewModel and Compose state.

🌍 Real-World Use Case

Notepad App can be used for:

* 📚 Study notes
* 💼 Work notes
* 💡 Quick ideas
* 📋 Personal reminders
* 🗂️ Categorized information
* 📝 Daily note-taking

For example, users can use different colors to distinguish work, study, personal, and important notes.

🎯 Project Goals

* Build a practical note-taking application
* Implement complete CRUD functionality
* Practice modern Android development
* Implement Firebase Firestore integration
* Implement custom Hex color handling
* Practice Kotlin Coroutines
* Build a clean Jetpack Compose interface
* Apply MVVM and Repository architecture

💼 Portfolio Highlights

Notepad App demonstrates practical experience with:

* Kotlin
* Jetpack Compose
* Firebase Firestore
* CRUD Operations
* MVVM Architecture
* Repository Pattern
* Kotlin Coroutines
* State Management
* Custom UI Components
* Hex Color Customization
* Modern Android Development
