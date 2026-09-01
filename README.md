# Focus OS 🎯

> **Ultimate Single-Page Study & Command Center** — Built with Vanilla HTML5, CSS3, JavaScript, Capacitor Android, and Firebase Real-time WebSockets.

Focus OS is a comprehensive productivity suite designed for students, developers, and deep-work enthusiasts. It seamlessly pairs across **Windows PC** and **Native Android Mobile** with zero latency, providing real-time cloud synchronization, study tracking, daily tasks, timetables, pomodoro sessions, and note-taking.

---

## ✨ Key Features

### ⚡ Real-Time Two-Way Cloud Sync
* **Instant Device Pairing:** Pair your PC and Mobile app instantly using a custom **Sync Key** (e.g. `FOCUS-7842`).
* **Firebase WebSockets & SSE:** Bidirectional updates sync changes live across devices with zero lag.

### 📊 Study Heatmap & Subject Tracking
* **26-Week GitHub-Style Heatmap:** Visualize study consistency over time.
* **Subject Analytics:** Log study hours, session counts, and completed goals per subject.
* **Interactive Calendar Logs:** Track daily study entries, reflection logs, and reference links.

### ⏱ Pomodoro Work Engine
* **Web Audio API Chimes:** Pure synthesized 4-tone ascending audio alerts on session completion.
* **Customizable Timers:** Focus, short break, and long break intervals.
* **Push Notifications:** Web & Native Android notifications for session finishes and task reminders.

### 📋 Daily Operations & Timetables
* **Daily Task Lists:** Manage daily to-do items with quick completion checkboxes and all-tasks history.
* **Color-Coded Timetables:** Build structured daily schedules categorized by domain (Cybersecurity, Dev, College, Rest, etc.).

### 📝 Notes & Quick Capture
* **Glassmorphic Note Editor:** Write, edit, and organize notes with instant auto-saving.
* **⚡ Quick Capture Overlay (`Ctrl + Space`):** Instantly add tasks or notes from anywhere in the app.

### 📱 Native Android Experience (Capacitor)
* **Futuristic Startup Animation:** Pulsating glowing splash screen with progress bar initialization.
* **Notch & Safe Area Clearance:** Custom safe-area insets for modern mobile edge-to-edge displays.
* **Floating Bottom Navigation Bar:** Quick single-tap switching between Dashboard, Study, Tasks, Notes, and Sync views.

---

## 🛠 Tech Stack

* **Frontend:** Vanilla HTML5, Vanilla CSS3 (Custom CSS Variables, Glassmorphism, CSS Grid & Flexbox), JavaScript (ES6+)
* **Mobile Runtime:** `@capacitor/core`, `@capacitor/android`, `@capacitor/local-notifications`
* **Real-time Backend:** Firebase Realtime Database (WebSockets & EventSource SSE)
* **Audio Engine:** Pure Web Audio API Synthesizer

---

## 🚀 Getting Started

### 1. Running on PC / Desktop Browser
Simply double-click `index.html` (inside `www/`) or run `Launch_Focus_OS.bat` / `Focus_OS.vbs` to launch the standalone desktop experience.

### 2. Running on Native Android Device
```bash
# Clone the repository
git clone https://github.com/Rishik-Nelluri/FocusOS.git
cd FocusOS

# Install dependencies
npm install

# Build and sync web assets to Android
npx cap sync

# Open project in Android Studio
npx cap open android
```
From Android Studio, hit **Run** to launch Focus OS directly on your connected physical Android phone or emulator.

---

## 📄 License
Created by [Rishik Nelluri](https://github.com/Rishik-Nelluri). Open source & available under the MIT License.
