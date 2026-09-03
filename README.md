# 📚 Timetable B

A simple, mobile-friendly timetable app for **B.Tech CSE — Section B**.

## ✨ Features

- 📅 Automatically opens on **today's timetable**
- 👆 Tap **Mon–Sat** to view another day
- ⏰ Shows class timings
- 📖 Shows subject names and course codes
- 📍 Shows the room/lab for each timetable entry
- 📱 Optimized for Android Chrome
- 🏠 Can be installed on the Android home screen as a PWA
- 🔄 Automatically recalculates the current day when opened

## 📱 Install on Android

1. Open the live app in **Chrome on Android**.
2. Open the Chrome menu **⋮**.
3. Choose **Add to Home screen** or **Install app**.
4. Add **Timetable B**.
5. Open it from your home screen like a normal app.

## 🌐 Live App

👉 **[Open Timetable B](https://chirantan112.github.io/Timetable-B/)**

## 🖥️ How It Works

The app is a lightweight static web app built with HTML, CSS and JavaScript. No backend or database is required.

When the app opens, JavaScript detects the current weekday and displays that day's timetable. The day buttons can be used to switch to another day manually.

## 📁 Project Structure

```text
Timetable-B/
├── index.html       # App UI, styling and timetable data
├── manifest.json    # PWA configuration
├── sw.js            # Service worker / offline caching
├── icon-192.png     # App icon
├── icon-512.png     # App icon
└── README.md        # Project documentation
```

## 📋 Timetable

The timetable data is based on the **3rd Semester Time Table 2026–27** document for **B.Tech. in CSE (Section B)**.

The app currently covers **Monday through Saturday**.

## 🛠️ Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Web App Manifest (PWA)
- Service Worker
- GitHub Pages

## 🚀 Deployment

The project is deployed using **GitHub Pages** from the `main` branch.

## ⚠️ Disclaimer

This is a personal student-made timetable app. It is not an official college timetable system. Always verify timetable changes with the latest official timetable issued by the university/department.
