# FoodBridge_AI

FoodBridge AI is an AI-powered food management and redistribution application designed to improve food safety, reduce food waste, and connect surplus food with people who need it.

## 📌 Problem Statement

Large amounts of edible food are wasted every day while many people face food insecurity. At the same time, it can be difficult to determine whether stored or donated food is still safe to consume.

FoodBridge AI aims to address these challenges by combining a mobile application, Firebase services, and machine learning.

## 💡 Solution

FoodBridge AI provides a platform for managing food-related information and uses machine learning models to support food risk and spoilage-related predictions.

The system consists of:

- Flutter mobile application
- Firebase backend services
- Python-based machine learning server
- Machine learning models for food-related prediction

## ✨ Key Features

- Food management
- Food safety/risk prediction
- Food spoilage prediction
- Volunteer-related functionality
- Firebase-based data management
- AI/ML-powered predictions
- Cross-platform Flutter application

## 🏗️ System Architecture

```text
                 FoodBridge AI
                       │
                       ▼
              Flutter Application
                       │
                       ▼
                    Firebase
                       │
                       ▼
                Python ML Server
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
     Food Risk     Spoilage      Volunteer
       Model        Model          Model
