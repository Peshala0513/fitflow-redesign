# FitFlow Frontend

Flutter application source code for the FitFlow fitness app.

## Purpose
This folder contains the cross-platform mobile and web client built with **Flutter**.

## Planned Structure

frontend/
├── lib/
│ ├── main.dart # App entry point
│ ├── screens/ # UI screens (Home, Workout, Nutrition, Community, Progress)
│ ├── widgets/ # Reusable UI components
│ ├── models/ # Data models
│ ├── services/ # API and backend communication
│ └── utils/ # Helper functions and constants
├── test/ # Unit and widget tests
└── pubspec.yaml # Flutter dependencies


## Key Features Implemented
- AI Daily Flow workout recommendations
- Camera-based nutrition logging
- Community challenges and social feed
- Progress tracking with visual charts
- Offline workout support

## Tech Stack
- **Framework:** Flutter (Dart)
- **State Management:** Riverpod / Bloc
- **AI Integration:** TensorFlow Lite (on-device)
- **Backend Communication:** REST API + Firebase SDK

## Status
📌 Structure planned — implementation pending.