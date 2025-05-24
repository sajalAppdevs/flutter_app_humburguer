![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)

# Flutter Hamburger App

A beautiful and modern Flutter application for a hamburger delivery service. This app showcases a clean UI design with smooth animations and intuitive user interactions.

## 📱 App Preview

<p align="center"><img src="https://github.com/iBy3l/flutter_app_humburguer/blob/main/hamb.gif"></p>

## ✨ Features

- Modern and intuitive UI design
- Smooth animations and transitions
- Hamburger menu categories
- Product listing with images and details
- Shopping cart functionality
- Bottom navigation with floating action button
- Responsive layout that works on various screen sizes

## 🛠️ Technologies Used

- Flutter SDK (>=2.12.0 <3.0.0)
- Dart programming language
- Material Design components
- Custom widgets and animations

## 🚀 Getting Started

### Prerequisites

- Flutter SDK installed on your machine
- An IDE (preferably Android Studio or VS Code)
- Basic knowledge of Flutter/Dart

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/flutter_app_humburguer.git
```

2. Navigate to the project directory:
```bash
cd flutter_app_humburguer
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the app:
```bash
flutter run
```

## 📁 Project Structure

```
lib/
├── main.dart            # App entry point
├── burguer_page.dart    # Detailed burger view
├── categories.dart      # Category listing
├── hamburguers_list.dart# Product listing
└── header.dart          # App header component
```

## 🎨 Theme Customization

The app uses a custom theme with amber as the primary color and red accents. You can modify the theme in `main.dart`:

```dart
theme: ThemeData(
  primaryColor: Colors.amber,
  cardColor: Colors.red,
  appBarTheme: AppBarTheme(color: Colors.amber, centerTitle: true),
  bottomAppBarColor: Colors.amber,
  floatingActionButtonTheme:
      FloatingActionButtonThemeData(backgroundColor: Colors.red),
)
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request.

## 📧 Contact

If you have any questions, feel free to reach out to the maintainers.

---

Made with ❤️ using Flutter
