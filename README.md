# FitFlow Redesign - HCI Project

## 📱 Project Description

**FitFlow** is a fitness tracking app redesign completed as part of the **IT3060 Human-Computer Interaction** course (Semester 2, 2026). The original app faced declining user retention and falling app store ratings, dropping from **4.6 to 3.8 stars** with **68% of users abandoning the app during onboarding**.

This redesign addresses three core user pain points identified through extensive user research:

| **Pain Point** | **User Evidence** |
|----------------|-------------------|
| **Lack of Personalization** | Generic, repetitive workout plans (INT-001, INT-003) |
| **Social Isolation** | Users feel alone and unmotivated (SURV-002, REVIEW-002) |
| **Tedious Nutrition Tracking** | Manual logging causes abandonment (INT-002, DIARY-002) |

## 🎯 Redesign Goal

To transform FitFlow from a declining product into an engaging, user-loved fitness companion by:

1. **AI-Powered Workout Plans** — Adaptive recommendations based on user's time, energy, and progress
2. **Social Community Features** — Challenges, accountability partners, and shared achievements
3. **Simplified Nutrition Tracking** — Camera-based food recognition and barcode scanning
4. **Improved Onboarding** — Streamlined first-time experience to reduce 68% churn rate

**Target Outcomes:**
- Increase user retention by **35%**
- Raise app store ratings to **4.5+ stars**
- Achieve **SUS score of 78+** in usability testing

## 🛠️ Recommended Tech Stack

| **Layer** | **Technology** | **Why It Was Selected** |
|-----------|---------------|-------------------------|
| **Frontend** | Flutter | 95%+ code reuse across iOS, Android, and Web with excellent animation performance |
| **Backend** | NestJS (Node.js) | TypeScript-first framework with strong real-time support and Firebase integration |
| **AI Service** | FastAPI (Python) | Best ML ecosystem for TensorFlow/PyTorch; ideal for personalization and food recognition |
| **Primary Database** | PostgreSQL | ACID compliance for health data; supports pgvector for AI features |
| **Real-Time Database** | Firebase Firestore | Native real-time updates for social feeds, challenges, and notifications |
| **Cache** | Redis | Fast session management, AI result caching, and rate limiting |
| **Authentication** | Firebase Auth | Easy setup with social login, MFA, and GDPR compliance |
| **Notifications** | Firebase Cloud Messaging | Push notifications for reminders, achievements, and social activity |

📖 **For full technology comparisons and justifications, see the [docs folder](docs/).**

## 📁 Repository Structure

fitflow-redesign/
│
├── README.md ← You are here
├── .gitignore
│
├── docs/ ← All documentation
│ ├── README.md
│ ├── tech-stack.md
│ ├── comparison-matrix.md
│ ├── architecture.md
│ ├── adr/
│ └── diagrams/
│
├── frontend/ ← Flutter app source code
│ └── README.md
│
├── backend/ ← Node.js API server
│ └── README.md
│
└── ai-service/ ← Python AI microservice
└── README.md


## 🔗 Quick Links

| **Document** | **Description** |
|--------------|-----------------|
| [Tech Stack](docs/tech-stack.md) | Full technology selection summary |
| [Comparison Matrix](docs/comparison-matrix.md) | Weighted decision matrix for all options |
| [Architecture](docs/architecture.md) | High-level system architecture and data flows |
| [ADRs](docs/adr/) | Architecture Decision Records (Frontend, Backend, Database, Auth) |
| [Diagrams](docs/diagrams/) | Visual architecture diagrams |

## 🚀 Project Status

| **Phase** | **Status** |
|-----------|------------|
| User Research (Labs 01–02) | ✅ Complete |
| Design & Wireframes (Lab 03) | ✅ Complete |
| Usability Testing (Lab 04) | ✅ Complete |
| Technology Selection (Lab 05) | ✅ Complete |
| Implementation | 📌 Planned |

## 👤 Author

- **W.A.P.U. Wijesinghe**
- Student ID: IT23864092
- Course: IT3060 - Human Computer Interaction
- Semester: 2, 2026
- Institution: Sri Lanka Institute of Information Technology (SLIIT)

## 📅 Course Information

| **Field** | **Details** |
|-----------|-------------|
| Module | IT3060 - Human Computer Interaction |
| Year | 3rd Year |
| Semester | 2nd Semester |
| Academic Year | 2026 |

---

*This repository contains all design artifacts, research findings, wireframes, usability test results, technology comparisons, and architecture documentation for the FitFlow redesign project.*