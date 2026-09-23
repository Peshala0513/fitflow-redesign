# ADR-003: Database Selection

**Status:** Accepted  
**Date:** 2026-08-16

## Context
FitFlow stores user profiles, workout logs, nutrition data, and social interactions. Health data requires ACID compliance.

## Decision
Use **PostgreSQL** as primary database and **Firebase Firestore** for real-time features.

## Rationale
- PostgreSQL: ACID compliance, health data handling, pgvector for AI
- Firestore: Real-time updates, offline support, easy integration
- Redis for caching and sessions

## Consequences
- Two database systems
- Data synchronization needed
- Higher complexity but better performance