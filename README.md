# 🥭 SnapMango - KitaHack 2026

**SnapMango** is an AI-powered nutrition and calorie tracking application developed for **KitaHack 2026**. Our mission is to leverage Google's cutting-edge technologies to contribute to the **Sustainable Development Goals (SDGs)**, specifically focusing on **SDG 3: Good Health and Well-being** and **SDG 2: Zero Hunger**.

## 🌟 Overview

Tracking nutrition is often a tedious and manual task. SnapMango simplifies this by allowing users to simply "Snap" a photo of their meal. Using a **Multi-Agent System powered by Google Gemini**, the app automatically identifies food items, estimates portion sizes, calculates nutritional data and tracks progress over time.

## 🚀 Key Features

- **AI Food Analysis**: Take a photo or upload from the gallery to get instant nutritional facts (Calories, Protein, Carbs, Fat, Fiber).
- **Multi-Agent Gemini System**: Utilizes specialized AI agents for classification, ingredient identification, and nutritional estimation.
- **Weekly Progress Tracking**: Visualized pie charts (powered by `fl_chart`) to monitor weekly calorie consumption against goals.
- **Personalized History**: A detailed log of all your past meals with high-contrast, easy-to-read reports.
- **Gamified User Experience**: Smooth transitions and an intuitive, "Mango-themed" UI designed for high engagement.
- **Secure Authentication**: Robust user management using Firebase Auth and Firestore.

## 🌍 SDG Alignment

SnapMango directly contributes to:
- **SDG 3 (Good Health & Well-being)**: By providing accessible tools for individuals to understand their nutritional intake and combat lifestyle-related diseases (obesity, diabetes).
- **SDG 2 (Zero Hunger/Nutrition)**: By promoting nutritional awareness and helping users optimize their food consumption.

## 🛠️ Technology Stack

- **Framework**: [Flutter](https://flutter.dev/) (Cross-platform)
- **AI Engine**: [Google Generative AI (Gemini 1.5 Flash)](https://ai.google.dev/)
- **Backend**: [Firebase](https://firebase.google.com/) (Auth, Firestore, Storage)
- **State Management**: [Riverpod](https://riverpod.dev/)
- **Charts**: [fl_chart](https://pub.dev/packages/fl_chart)
- **Environment**: [flutter_dotenv](https://pub.dev/packages/flutter_dotenv)

## 🧰 Technical Architecture

![image alt](https://github.com/wei-leong/kitahack_2026/blob/6e22c42e27023af3d0661136fc7bfdcaf4abc271/SnapMango_Technical%20Architecture.png)

## 📦 Getting Started

### Prerequisites
- Flutter SDK (latest stable version)
- A Google Gemini API Key
- A Firebase project

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/kitahack_2026.git
   cd kitahack_2026
   ```

2. **Setup Environment Variables**:
   Create a `.env` file in the root directory and add your Gemini API Key:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

3. **Install dependencies**:
   ```bash
   flutter pub get
   ```

4. **Run the application**:
   ```bash
   flutter run
   ```

---
