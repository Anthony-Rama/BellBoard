# 📣 BellBoard  
*A cross-platform digital bulletin board app built by Hofstra University's largest senior design team.*

![Flutter](https://img.shields.io/badge/Built%20With-Flutter-blue.svg)  
![Firebase](https://img.shields.io/badge/Backend-Firebase-FFCA28.svg)  
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## 🏫 Project Overview

**BellBoard** is a real-time, cross-platform bulletin board application developed by a six-person senior design team at **Hofstra University**. This ambitious project—part of the university’s largest senior design initiative to date—aims to modernize campus communication by combining **software and hardware into a unified experience**.

BellBoard is not just a digital application. It is designed to **pair with a custom-built physical display board**, enabling users to post announcements through the app that are **mirrored in real-time** on a public physical screen via IoT integration. This hybrid approach ensures wide accessibility—both digitally and in-person.

---

## 🔧 Key Features

- 🔔 **Dynamic Bulletin Feed** – Create, edit, and view announcements instantly  
- 🌐 **Cross-Platform App** – Runs on Android, iOS, Web, macOS, Windows, and Linux  
- 🔒 **Firebase Authentication** – Secure login and account management  
- 🧑‍⚖️ **Role-Based Access Control** – Admins, staff, and general users have tailored permissions  
- 🖼️ **Rich Media Support** – Upload images, flyers, and formatted messages  
- 🔍 **Search & Filter** – Quickly locate posts by tag, type, or date  
- 📅 **Time-Based Scheduling** – Set post lifespans or display durations  
- 📺 **Hardware Sync** – Posts pushed to a physical LED/monitor display in real time  

---

## 🔌 Hardware Integration

The **physical BellBoard** is a custom-built smart bulletin board designed to receive data from the app via cloud services. Built using microcontroller-based display technology, it connects to Firebase and updates dynamically as new announcements are posted in the app.

- Powered by a microcontroller with network capability (e.g. Raspberry Pi or ESP32)  
- Connects to Firestore to fetch and display messages  
- Displays important campus alerts or daily schedules on public monitors  

---

## 🛠️ Tech Stack

| Layer               | Technology                |
|---------------------|----------------------------|
| **Frontend**        | Flutter (Dart)             |
| **Backend**         | Firebase (Auth, Firestore) |
| **Hardware Sync**   | Firebase SDK, IoT Display  |
| **State Management**| Provider                   |
| **CI/CD**           | GitHub Actions             |

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

