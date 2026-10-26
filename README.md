# ClikkMe — Social Media App (Flutter)

A Flutter social media app that talks to a MERN-stack backend API. The app
covers the usual social flow — accounts, feed and profiles — and is built with
a clean, BLoC-based structure so features stay easy to extend.

The companion web/backend project is
[social-app-mern](https://github.com/sahilmyadav/social-app-mern), and API
notes live in `api_docs.md` in this repository.

## Features

- Sign up / login with secure token storage
- Social feed and profile screens
- BLoC state management (`flutter_bloc`) with `get_it` dependency injection
- Networking with Dio and local storage with shared preferences

## Tech Stack

- Flutter / Dart (SDK >= 3.2.0)
- flutter_bloc, equatable, get_it
- dio, flutter_secure_storage, shared_preferences
- google_fonts, font_awesome_flutter

## Getting Started

```bash
flutter pub get
flutter run
```

Make sure the backend API is running and update the API base URL in the app
config to point at it.

## Project Structure

```
lib/          App code (features, blocs, services)
api_docs.md   Backend API documentation
android/ ios/ web/   Platform shells
```
