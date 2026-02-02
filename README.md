# 🎯 First Flutter App

My first Flutter application! This project demonstrates core Flutter concepts through a simple yet functional random word pair generator with favorites management.

## 📱 About The App

This app was built as a learning project for Flutter development. While named "EmedQ Question Bank" (MBBS question bank app with in-app model answers, offline support, and Firebase sync for Tamil Nadu students), it currently implements a random word pair generator with the following features:

- **Random Word Generation**: Generate random English word pairs at the tap of a button
- **Favorites Management**: Like and save your favorite word pairs
- **Responsive Navigation**: Adaptive navigation rail that extends on larger screens
- **Modern UI**: Clean Material Design interface with a green accent theme

## ✨ Features

- 🎲 Generate random word pairs using the `english_words` package
- ❤️ Add/remove word pairs to/from favorites
- 📱 Responsive layout that adapts to different screen sizes
- 🎨 Material Design with custom color scheme
- 🔄 State management using Provider pattern

## 🛠️ Built With

- **Flutter SDK**: 3.10.4+
- **Dart**: Latest stable version
- **State Management**: Provider (^6.1.5)
- **Random Words**: english_words (^4.0.0)

## 📦 Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter
  english_words: ^4.0.0
  provider: ^6.1.5
  cupertino_icons: ^1.0.8

dev_dependencies:
  flutter_test:
    sdk: flutter
  flutter_lints: ^6.0.0
```

## 🚀 Getting Started

### Prerequisites

- Flutter SDK 3.10.4 or higher
- Dart SDK
- Android Studio / VS Code with Flutter extensions
- An emulator or physical device for testing

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mdcreator-2/First-Flutter-App.git
   cd First-Flutter-App
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

### Platform Support

This app supports multiple platforms:
- ✅ Android
- ✅ iOS
- ✅ Web
- ✅ Windows
- ✅ macOS
- ✅ Linux

## 📖 What I Learned

Building this app helped me understand:

1. **Flutter Basics**
   - Widget tree structure
   - StatelessWidget vs StatefulWidget
   - Hot reload functionality

2. **State Management**
   - Using Provider for state management
   - ChangeNotifier pattern
   - Separating business logic from UI

3. **UI Components**
   - Material Design widgets
   - Navigation rail for app navigation
   - Responsive layouts with LayoutBuilder
   - Creating custom widgets (BigCard)

4. **Flutter Architecture**
   - Project structure
   - Package management with pubspec.yaml
   - Platform-specific code organization

## 🎨 App Structure

```
lib/
├── main.dart          # Main application entry point
│   ├── MyApp          # Root widget with ChangeNotifierProvider
│   ├── MyAppState     # Application state management
│   ├── MyHomePage     # Main navigation scaffold
│   ├── GeneratorPage  # Word pair generator page
│   ├── FavoritesPage  # Favorites display page
│   └── BigCard        # Custom card widget for displaying words
```


## 🤝 Contributing

This is a learning project, but suggestions and feedback are welcome! Feel free to:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available for educational purposes.

## 👤 Author

**mdcreator-2**

- GitHub: [@mdcreator-2](https://github.com/mdcreator-2)

## 🙏 Acknowledgments

- Flutter team for the amazing framework and documentation
- [Flutter Codelabs](https://docs.flutter.dev/codelabs) for the learning resources
- The Flutter community for support and inspiration

---

⭐️ If this helped you learn Flutter, feel free to star the repo!
