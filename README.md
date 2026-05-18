# AIDE Mobile

AIDE Mobile is a Flutter app for controlling and managing an AIDE robot system. It brings together role-based authentication, robot controls, live status views, Firebase-backed user management, and setup tools for admins and operators.

## Highlights

- Admin and operator login flows
- Firebase Authentication and Cloud Firestore integration
- Robot control screens for manual drive and person-follow modes
- Live feed and robot telemetry UI
- Admin setup and user management tools
- Settings, profile, help, privacy, and localization screens
- Android, iOS, web, Windows, macOS, and Linux Flutter targets

## Tech Stack

- Flutter / Dart
- Firebase Core
- Firebase Authentication
- Cloud Firestore
- SharedPreferences
- HTTP services
- WebView Flutter

## Getting Started

Install dependencies:

```bash
flutter pub get
```

Run the app:

```bash
flutter run
```

Run tests:

```bash
flutter test
```

## Project Notes

Firebase configuration is included for the current app setup. Review Firebase project settings, Firestore rules, and admin credentials before production use.
