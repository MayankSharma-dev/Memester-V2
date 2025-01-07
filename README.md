# Memesterr-V2: A Reddit Client for Android (Educational Purpose)

Memesterr is a Reddit client for Android specifically designed to showcase memes and deliver an engaging and user-friendly experience for meme enthusiasts. The app features several key functionalities that allow users to browse, bookmark, search, and share memes seamlessly, along with offline support and modern Android development practices.

This project is intended for educational purposes to demonstrate various concepts of Android development, including the use of Google authentication, real-time data management, encryption, and modern app architecture.

## Key Features

- **Google One Tap Sign-In**: Provides a seamless authentication experience for users.
- **Firestore Integration**: Real-time data management for a dynamic and responsive app experience.
- **Android Keystore**: Securely stores sensitive data such as API keys using Android’s built-in encryption.
- **Network Bound Resource**: Efficient refresh logic and caching for better performance and user experience.
- **Offline Support**: Access and browse memes even without an internet connection.

## Demo
 <video width="320" height="240" src="https://github.com/user-attachments/assets/1d9580bc-9cdc-423d-a718-fb96cbc52e3d" type="video/mp4"> Your browser does not support the video tag. </video>
//Here is the video demo

## Key Functionalities

- **Browse Memes**: View the latest trending memes from Reddit in a clean, engaging interface.
- **Bookmark Memes**: Save your favorite memes for easy access later.
- **Search Memes**: Easily search for specific memes or topics using a built-in search feature.
- **Share Memes**: Share memes directly with your friends or on social media platforms.
- **Endless Scrolling**: Smooth infinite scroll to continuously browse memes without interruptions.
- **Auto Video Playback**: Automatically plays or pauses meme videos as you scroll.

## Tech Stack

- **Jetpack Compose**: For building a modern, declarative UI that is efficient and easy to maintain.
- **Firestore**: For real-time data management and syncing content.
- **Android Keystore**: To encrypt and securely store sensitive data.
- **Network Bound Resource**: To manage network requests and local caching efficiently.
- **Coroutines and Flow**: To handle asynchronous tasks with minimal boilerplate code.

## Architecture

This app follows modern architectural practices, including:

- **MVVM (Model-View-ViewModel)**: To separate concerns and keep the UI logic clean and maintainable.
- **Repository Pattern**: To abstract data sources and provide a clean interface to the ViewModel.
- **Use of Kotlin Flows**: For asynchronous programming and reactive UI updates.
- **Hilt for Dependency Injection**: To manage dependencies efficiently and keep the code decoupled.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/memesterr-v2.git
   ```
2. **Open the project in Android Studio:**

Open Android Studio and navigate to the directory where the project is cloned.

3. **Configure Firebase:**

1. Go to the Firebase Console: [Firebase Console](https://console.firebase.google.com/).
2. Create a new Firebase project or select an existing one.
3. Add Firebase Authentication and Realtime Database to your project.
4. Download the `google-services.json` file from the Firebase console and place it in the `app/` directory of your project.

4. **Build and Run:**

1. Build the project by clicking on `Build > Make Project`.
2. Connect an Android device or start an emulator.
3. Run the application from Android Studio by clicking the `Run` button.

---

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request and describe your changes.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
