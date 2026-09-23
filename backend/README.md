# FitFlow Backend

Node.js API server source code for the FitFlow fitness app.

## Purpose
This folder contains the core REST API and real-time services built with **Node.js and NestJS**.

## Planned Structure

backend/
├── src/
│ ├── main.ts # Application entry point
│ ├── modules/
│ │ ├── auth/ # Firebase Auth integration
│ │ ├── users/ # User profile management
│ │ ├── workouts/ # Workout CRUD operations
│ │ ├── nutrition/ # Nutrition logging endpoints
│ │ ├── social/ # Community and challenges
│ │ └── notifications/ # Push notifications
│ ├── common/ # Guards, interceptors, filters
│ └── config/ # Environment configuration
├── test/ # Unit and integration tests
└── package.json # Node dependencies



## Key Responsibilities
- User authentication and authorization
- Workout plan CRUD operations
- Nutrition data management
- Social features (challenges, feeds, partners)
- Real-time communication via Socket.io
- Push notification orchestration

## Tech Stack
- **Framework:** Node.js + NestJS (TypeScript)
- **Database:** PostgreSQL (primary) + Firebase Firestore (real-time)
- **Cache:** Redis
- **Auth:** Firebase Authentication
- **Real-time:** Socket.io

## Status
📌 Structure planned — implementation pending.