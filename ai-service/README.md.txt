# FitFlow AI Service

Python microservice for AI-powered features in the FitFlow app.

## Purpose
This folder contains the AI microservice built with **Python and FastAPI**. It handles personalization, food recognition, and workout recommendation logic.

## Planned Structure

ai-service/
├── app/
│ ├── main.py # FastAPI application entry point
│ ├── models/
│ │ ├── workout_engine.py # AI workout recommendation logic
│ │ ├── food_recognition.py# Camera-based food recognition
│ │ └── personalization.py # User preference learning
│ ├── routes/ # API endpoints
│ └── utils/ # Helper functions
├── requirements.txt # Python dependencies
└── test/ # Unit tests


## Key Responsibilities
- Generate personalized workout plans based on user input
- Recognize food items from camera images
- Learn user preferences over time
- Analyze progress and suggest adaptations
- Provide trainer AI modification suggestions

## Tech Stack
- **Framework:** Python + FastAPI
- **ML Libraries:** TensorFlow, PyTorch, TensorFlow Lite
- **Model Serving:** ONNX Runtime / TensorFlow Serving
- **Communication:** REST API (called by backend)

## Status
📌 Structure planned — implementation pending.