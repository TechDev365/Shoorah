<p align="center">
  <img src="https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/e0/38/ef/e038efb8-7c20-c804-ce7f-909f0cf3eb33/AppIcon-0-0-1x_U007emarketing-0-7-0-85-220.png/230x0w.webp" width="120" alt="Shoorah App Logo" />
</p>

<h1 align="center">🌿 Shoorah – Mental Health & Calm</h1>

<p align="center"><em>"Calm mind brings inner strength and self-confidence."</em></p>

![Shoorah Image](https://shoorah.io/wp-content/uploads/2024/08/Untitled-design-3-1.jpg.webp)

---

## 🔽 Available on Your Favorite Platform

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.shoorah&hl=en_IN">
    <img height="83" width="200" alt="Get it on Google Play" src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png"/>
  </a>
  <a href="https://apps.apple.com/in/app/shoorah-mental-health/id1669683359">
    <img height="83" width="180" alt="Download on the App Store" src="https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/en-us?size=200x83"/>
  </a>
</p>

---

## 🧑‍💻 Technical Overview

Shoorah is built using **Flutter** and follows a clean, scalable **feature-first architecture** that promotes modularity and testability.

### 🏗️ Project Structure
<pre>
lib/
├── core/
│ ├── base/ # Base models, error types
│ ├── common_widgets/ # Reusable UI widgets
│ ├── constant/ # Constants, enums, styles, assets
│ ├── localization/ # Internationalization
│ ├── network/ # Networking layer
│ └── utils/ # Utility functions
│
├── di/
│ └── injector.dart # Dependency injection config
│
├── features/
│ ├── data/
│ │ ├── modal/ # Data models
│ │ └── repository_implementation/
│ ├── domain/
│ │ ├── repository/
│ │ └── usecases/
│ └── presentation/ # UI Layer
│ ├── about/
│ ├── category/
│ ├── change_password/
│ ├── choose_theme/
│ ├── dashboard/
│ ├── discover_serenity/
│ ├── downloads/
│ ├── edit_profile/
│ ├── explore/
│ ├── forgot_password/
│ ├── free_trial/
│ ├── home/
│ ├── journal/
│ ├── login/
│ └── maintenance/
│
├── firebase_options.dart
└── main.dart
</pre>
---

### 🧱 Architecture

The project is structured using the **Clean Architecture** principle:

| Layer         | Responsibility                                     |
|---------------|-----------------------------------------------------|
| Presentation  | UI widgets and state management (Bloc)             |
| Domain        | Business logic (UseCases, Repository Abstraction)  |
| Data          | Remote/local data sources and models               |
| Core/DI       | Utilities, shared constants, and DI config         |

---

### 🧰 Tech Stack

| Category      | Tool/Library           |
|---------------|------------------------|
| Framework     | Flutter, Dart          |
| Architecture  | Clean Architecture, BLoC |
| Backend       | Firebase (Auth, Firestore, Analytics) |
| Networking    | REST APIs (Dio)        |
| UI/UX         | Figma, Custom widgets  |
| Localization  | Flutter Intl           |
| State Mgmt    | BLoC                   |
| Design Assets | Lottie, SVG            |

---

### 🔄 State Management: BLoC

Each feature uses its own Bloc pattern. For example:
<pre>
features/
└── category/
├── bloc/
│ ├── category_bloc.dart
│ ├── category_event.dart
│ └── category_state.dart
└── widget/
└── category_drop_down.dart
</pre>
This ensures clean separation of concerns, testability, and scalability.

---

## ✨ Challenges, Collaboration, and Success

### 📍 The Challenge: Balancing Empathy with Tech

> Create a mental health app that’s both technically reliable and emotionally sensitive. We tackled:
> - Data privacy & secure Firebase integration
> - Intuitive UX for vulnerable users
> - Scalable, single Flutter codebase

### 📍 Agile Collaboration with Shoorah Inc.

> We worked in sprints with regular feedback via Slack & Figma. Domain knowledge from the Shoorah team merged with our tech skills to shape the final product.

### 📍 Success Milestone

> Shoorah reached **1000+ downloads** in its first month, validating both its usability and emotional impact.

---

## 🔍 Feature Highlights

### 🧘 Discover Yourself
Empowering tools for self-awareness and growth.

![Self Development](https://play-lh.googleusercontent.com/Xihavky1P8DZoF54zuKrRl-B5Ow3h8xPfoRxa_jKzlQaqzJxgA5T6PFO1p6B8MX2_IQ=w526-h296-rw)

---

### 🎧 Calm Your Mind

> Premium audio content like:
- Guided meditations
- Breathwork exercises
- Sleep sounds

![Calm](https://play-lh.googleusercontent.com/yPO8A3VAp2cH1fg5YShJ3Oblwdrsl4TGj8t9hsqlmPzsyWRQ7U2mxkEP_3701nOD-ts=w526-h296-rw)

---

### 🌞 Daily Motivation

> “I am grateful for my life.”  
Daily affirmations to start your day with strength.

![Motivation](https://play-lh.googleusercontent.com/gPKaGXu-3sul5rTC8CzXB0yooX7CAfBPO4FE-7L9cW7zOcuWLr0MDiOBE2-JrFbW6ew=w526-h296-rw)

---

### 👤 Personalized Dashboard

Track your emotional journey and milestones visually.

![Dashboard](https://play-lh.googleusercontent.com/gPKaGXu-3sul5rTC8CzXB0yooX7CAfBPO4FE-7L9cW7zOcuWLr0MDiOBE2-JrFbW6ew=w526-h296-rw)

---

### 🧠 Self-Assessment Tools

Take science-backed quizzes like the **Social Anxiety Test**.

![Assessment](https://play-lh.googleusercontent.com/AogXfOR_ALKnNmFqF8ShibAzbROo2JL7dkrzKE04MW7svlamLkrpNvfP-5947cPEFuA1=w526-h296-rw)

---

## 📊 App Stats

| Platform             | Rating     | Downloads    |
|----------------------|------------|--------------|
| Apple App Store      | ⭐️⭐️⭐️⭐️⭐️ (5.0) | 10K+         |
| Google Play Store    | ⭐️⭐️⭐️⭐ (3.7)   | 10K+         |

---

## 🧾 License

All rights reserved © Shoorah Inc. This codebase is proprietary and protected by intellectual property rights.

---

## 💬 Final Note

> *“Your peace of mind is the foundation for everything else. Shoorah helps you build it.”*

Make space for your wellbeing.  
Make time for your growth.  
Make **Shoorah** your daily companion.

---
