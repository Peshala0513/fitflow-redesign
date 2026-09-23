# FitFlow High-Level Architecture

## Overview

FitFlow uses a client-server architecture with an AI microservice, real-time data layer, and secure authentication.

## Components

| Component | Technology | Purpose |
|-----------|-----------|---------|
| Client Apps | Flutter | iOS, Android, Web frontends |
| API Gateway | NGINX | Routing, load balancing |
| Core API | NestJS | Business logic, CRUD operations |
| AI Service | FastAPI (Python) | Workout recommendations, food recognition |
| Primary DB | PostgreSQL | Users, workouts, nutrition, progress |
| Real-time DB | Firebase Firestore | Social feeds, challenges, notifications |
| Cache | Redis | Sessions, AI cache, rate limiting |
| Auth | Firebase Auth | Login, social auth, MFA |
| Storage | Firebase Storage | Meal photos, workout videos |
| Notifications | Firebase Cloud Messaging | Push notifications |

## Data Flows

### 1. Personalized Workout Plan
User input → Flutter → API Gateway → NestJS → AI Service → TensorFlow Lite → PostgreSQL → Redis cache → Flutter

### 2. Social Sharing
User action → Flutter → API Gateway → NestJS → Firestore (real-time) → Socket.io → Friends' devices

### 3. Nutrition Tracking
Camera photo → Flutter → API Gateway → FastAPI → TensorFlow Lite (food recognition) → Nutrition DB → PostgreSQL → Daily summary

## Security

- TLS 1.3 for all communication
- AES-256 encryption at rest
- JWT tokens with Firebase Auth
- GDPR and CCPA compliant
- Rate limiting and input validation

## Scalability

- Horizontal scaling for NestJS and FastAPI
- PostgreSQL read replicas
- Redis Cluster
- Firebase auto-scaling
- CDN for static assets

## Architecture Diagram

See `architecture-diagram.png` in this folder for the visual representation.