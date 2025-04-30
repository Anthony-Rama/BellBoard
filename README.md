# 🧗 BellBoard  
*A cross-platform social and route management app designed to pair with a custom-built smart rock climbing board.*

![Flutter](https://img.shields.io/badge/Built%20With-Flutter-blue.svg)  
![Firebase](https://img.shields.io/badge/Backend-Firebase-FFCA28.svg)  
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## 🧩 Project Overview

**BellBoard** is a mobile-first, cross-platform application built to **improve accessibility in the rock climbing community** by combining social networking, custom route creation, and a physical smart climbing wall — all in one system. 

This app was developed by a six-person senior design team at **Hofstra University**, as part of the school’s largest senior design project to date. The goal was to create a **more affordable and community-focused alternative** to expensive proprietary climbing boards and apps on the market.

BellBoard connects directly to a **custom-built LED rock climbing board**, enabling users to display routes, create problems, and climb interactively. The app also features a **social feed**, allowing users to follow each other, like, comment, and engage with climbing content.

---

## 🔧 Key Features

- 🔐 **Login & Account Creation** – Firebase authentication for secure sign-up and login  
- 🧗 **Custom Route Builder** – Create your own climbing problems and assign grades  
- 🧠 **Preset Routes** – Built-in problems for Beginner, Intermediate, and Expert levels  
- 📲 **Board Integration** – Send custom or preset routes directly to the physical board  
- 📸 **Climbing Social Feed** – Post, like, comment, follow, and share beta with other users  
- 🔍 **Search for Climbers** – Find and connect with users by username  
- 📈 **Community Growth** – Build and follow climbers' progress, solve new problems daily  
- 🧱 **Affordable + Open Design** – Designed as a low-cost, accessible solution for at-home or gym use  

---

## 🔌 Hardware Pairing

The app connects with a **custom-built rock climbing wall** featuring:

- Addressable LED holds powered by a microcontroller (e.g. Raspberry Pi or ESP32)  
- Firebase cloud communication for real-time route syncing  
- Physical route display based on user selection or custom creation  
- Bidirectional sync for app-to-wall route control and preview  

---

## 🛠️ Tech Stack

| Layer                 | Technology                          |
|-----------------------|--------------------------------------|
| **Frontend**          | Flutter (Dart)                       |
| **Backend**           | Firebase (Authentication, Firestore, Storage, Realtime Database) |
| **Authentication**    | Firebase Auth (Email/Password)       |
| **Social Features**   | Firestore (likes, comments, follows, posts) |
| **Route Management**  | Firestore + Custom Logic              |
| **Hardware Sync**     | Firebase SDK, ESP32/Raspberry Pi, LED Matrix |
| **State Management**  | Provider                             |
| **CI/CD**             | GitHub Actions                       |

---

## ⚙️ Getting Started

### Prerequisites

- Flutter SDK  
- Firebase project (set up using Firebase CLI or console)  
- Emulator/device or physical deployment target  

### Setup

```bash
git clone https://github.com/Anthony-Rama/BellBoard.git
cd BellBoard
flutter pub get
flutter run
```
---
## 📄 License

This project is licensed under the MIT License.

---
## 📬 Contact

For questions, feature requests, or demo inquiries, please open an issue on GitHub.

