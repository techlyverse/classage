# 📚 Classage

**Classage is a modern educational classroom and video conferencing application built with Flutter and Firebase. It provides a comprehensive platform for teachers and students to connect, learn, and manage academic activities seamlessly.**

## 🌟 Key Features

Classage is designed to replicate and enhance the physical classroom experience in a digital format, offering:

* **Live Video Conferencing:** Initiate and join real-time video sessions for lectures and discussions (Inferred from "video conferencing classroom app").
* **Secure Authentication:** User sign-up and login for both students and teachers, powered by Firebase.
* **Instant Messaging & Chat:** Dedicated chat features for class communication and private discussions.
* **Digital Library:** A section to manage and access educational resources and materials.
* **Tests & Assessments:** Functionality to conduct, submit, and view results for tests and quizzes.
* **Cross-Platform Compatibility:** Built with Flutter, the app can run natively on Android and iOS, and also as a web application.

## 🛠️ Built With

* **Frontend:** [Flutter](https://flutter.dev/) (Primary language: Dart)
* **Backend:** [Firebase](https://firebase.google.com/) (For Authentication, Database, and Storage)

## 🚀 Getting Started

Follow these instructions to set up and run the project locally for development and contribution.

### Prerequisites

You need the following installed on your system:

1.  **Flutter SDK:** [Install Flutter](https://flutter.dev/docs/get-started/install)
2.  **Dart SDK:** (Comes bundled with Flutter)
3.  **Code Editor:** [VS Code](https://code.visualstudio.com/) or [Android Studio](https://developer.android.com/studio)
4.  **Firebase CLI:** For connecting and deploying to your Firebase project.

### Local Installation

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/techlyverse/classage.git](https://github.com/techlyverse/classage.git)
    cd classage
    ```

2.  **Install Dependencies**
    ```bash
    flutter pub get
    ```

3.  **Firebase Setup (Crucial Step)**
    Since this project uses Firebase, you must connect it to your own Firebase project for the app to function.
    * Create a new project in the [Firebase Console](https://console.firebase.google.com/).
    * Add an Android app and an iOS app to your Firebase project, following the console instructions.
    * Download the configuration files: `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) and place them in the correct directories (`android/app` and `ios/Runner`, respectively).
    * **Note:** If you are using the modern FlutterFire CLI, you can skip the manual download and run `flutterfire configure`.

4.  **Run the App**
    Connect a device or start an emulator/simulator, and then run:
    ```bash
    flutter run
    ```

## 📱 Screenshots

| Welcome Screen | Teacher Dashboard | Chats View | Library |
| :---: | :---: | :---: | :---: |
| ![[welcome](https://github.com/RaghvShukla/classage/raw/master/images/welcome.png)](https://github.com/RaghvShukla/classage/raw/master/images/welcome.png) | ![[teacher](https://github.com/RaghvShukla/classage/raw/master/images/teacher.png)](https://github.com/RaghvShukla/classage/raw/master/images/teacher.png) | ![[chats](https://github.com/RaghvShukla/classage/raw/master/images/chats.png)](https://github.com/RaghvShukla/classage/raw/master/images/chats.png) | ![[library](https://github.com/RaghvShukla/classage/raw/master/images/library.png)](https://github.com/RaghvShukla/classage/raw/master/images/library.png)

*The screenshots above are sourced from the project's original asset links.*

## 💡 Contributing

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'feat: Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request
