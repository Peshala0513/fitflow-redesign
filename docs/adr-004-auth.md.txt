# ADR-004: Authentication Selection

**Status:** Accepted  
**Date:** 2026-08-16

## Context
FitFlow needs secure authentication with social login, MFA, and GDPR compliance.

## Decision
Use **Firebase Authentication**.

## Rationale
- Seamless integration with Flutter and NestJS
- Social login (Google, Apple, Facebook)
- MFA support
- GDPR compliant
- Generous free tier

## Consequences
- Vendor lock-in with Firebase
- Limited UI customization
- Data stored on Google Cloud