# Flash Chat 

A modern, real-time messaging app built with Flutter and Firebase. Users can register, log in, and send messages in a group chat, with all data stored and retrieved instantly from a cloud-based NoSQL database.

## About The Project

The main objective of this project was to learn how to integrate **Firebase** into a Flutter application. It covers the two most important aspects of Firebase: **Authentication** for secure user sign-up/sign-in and **Cloud Firestore** for a real-time cloud database. The app also features beautiful, custom animations to create a polished user experience.

## Key Features & Concepts

This project was an opportunity to build a full-stack application and master several key concepts:

* **Firebase Integration:**
    * **Firebase Authentication:** Securely register and sign in users with email and password.
    * **Cloud Firestore:** Use a cloud-based NoSQL database to store and retrieve messages in real-time.
* **Real-time Data with Streams:**
    * Understand and use Dart `Streams` to listen for live changes in the Firestore database and automatically update the UI.
* **Advanced Flutter Animations:**
    * Create beautiful screen transitions using Flutter's `Hero` widget.
    * Build custom, high-performance animations from scratch using `AnimationController` and `Mixins`.
* **Flutter & Dart Core Concepts:**
    * **Mixins:** Understand what mixins are, how they differ from inheritance, and when to use them (e.g., for animation controllers).
    * **ListViews:** Use `ListView` and `StreamBuilder` to efficiently build scrolling lists that update in real-time.
    * **Navigation:** Implement robust navigation between screens.

## Built With

* **[Flutter](https://flutter.dev/)** - The UI toolkit for building beautiful, natively compiled applications.
* **[Dart](https://dart.dev/)** - The programming language used by Flutter.
* **[Firebase](https://firebase.google.com/)** - The platform for building the app's backend.
    * **Firebase Authentication**
    * **Cloud Firestore**

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* **Flutter SDK:** [Installation Guide](https://flutter.dev/docs/get-started/install)
* **An IDE:** VS Code or Android Studio.
* **A Firebase Project:** You must create your own Firebase project to connect the app.

### Installation & Setup

1.  **Set up your Firebase Project**
    * Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project.
    * Register your app for iOS and/or Android.
    * Follow the instructions to add the `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) files to your Flutter project.
    * In the console, enable **Authentication** (with the Email/Password provider) and **Cloud Firestore**.

2.  **Clone the repo**
    ```sh
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```
3.  **Navigate to the project directory**
    ```sh
    cd your-repository-name
    ```
4.  **Install dependencies**
    ```sh
    flutter pub get
    ```
5.  **Run the app**
    ```sh
    flutter run
    ```

---
