# ADR-001: Frontend Framework Selection

**Status:** Accepted  
**Date:** 2026-08-16

## Context
FitFlow needs a mobile app for iOS and Android with potential web expansion, complex animations, and AI integration.

## Decision
Use **Flutter** as the primary frontend framework.

## Rationale
- 95%+ code reuse across iOS, Android, and Web
- Excellent performance with compiled Dart and Impeller
- Strong AI/ML integration (TensorFlow Lite)
- Rich widget library for fitness UX
- Hot reload for rapid development

## Consequences
- Team needs Dart training
- Larger app size than native
- Web support still maturing