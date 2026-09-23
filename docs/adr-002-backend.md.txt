# ADR-002: Backend Framework Selection

**Status:** Accepted  
**Date:** 2026-08-16

## Context
Backend needs to handle real-time social features, AI integration, and scale for 10,000+ concurrent users.

## Decision
Use a **hybrid microservices architecture**: Node.js/NestJS for core API and Python/FastAPI for AI services.

## Rationale
- NestJS: TypeScript, real-time (Socket.io), Firebase integration
- FastAPI: Best ML ecosystem (TensorFlow, PyTorch)
- Separation allows independent scaling

## Consequences
- Two backend languages to maintain
- API gateway required
- More complex deployment