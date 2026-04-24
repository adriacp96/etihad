<div align="center">

<img src="assets/images/etihadbus.png" alt="Etihad Bus Logo" width="100">

# Etihad Bus

**Live bus schedules, right on your device.**

[![PWA Ready](https://img.shields.io/badge/PWA-Ready-5A0FC8?style=flat-square&logo=pwa)](https://adriacp96.github.io/etihad/)
[![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen?style=flat-square)](#)
[![Dark Mode](https://img.shields.io/badge/dark%20mode-supported-1a1a2e?style=flat-square)](#)

[**Open App →**](https://adriacp96.github.io/etihad/)

</div>

---

## What is Etihad Bus?

Etihad Bus is a lightweight, installable web app for viewing bus schedules between CBC and crew accommodations. No login, no backend — just open it and see when your next bus leaves.

---

## Features

| Feature | Description |
|---|---|
| 📍 **Auto-Location** | Automatically detects if you are at CBC or your accommodation to set your route |
| 🏠 **Custom Home** | Save your exact GPS coordinates to your preferred stop for precise auto-detection |
| 📶 **Offline Ready** | Fully cached via Service Workers to work instantly without an internet connection |
|  **Next Departure** | See the next bus and a live countdown in seconds |
| 🗺️ **Live Route Map** | Animated bus positions along the route in real time |
| 🔄 **Both Directions** | Toggle between *From CBC* and *To CBC* |
| ⌚ **Briefing Planner** | Calculate which bus you need to take to be always on time |
| ✈️ **Layover Mode** | Interactive comic screensavers automatically activate when you're outside Abu Dhabi |
| 🌙 **Dark Mode** | Automatically follows your device's theme |
| 📲 **Install as App** | Add to Home Screen on iOS or Android for a native feel |
| 💾 **Remembers You** | Your last route, stop, and direction are saved locally |
| 📋 **Full Schedule** | Scrollable timetable with the next bus highlighted |
| ⛶ **Fullscreen Mode** | Big-clock countdown view — great for glancing from a distance |

---

## Routes

Etihad Bus currently covers the following routes running 24 hours a day:

| Route | Key Stops |
|---|---|
| **Masdar 2** | CBC ↔ Masdar 2 |

---

## How to Use

1. **Open** the app at [adriacp96.github.io/etihad](https://adriacp96.github.io/etihad/)
2. **Use Auto Mode** to let GPS instantly set your route and direction, OR
3. **Pick manually** by choosing your route, stop, and direction from the dropdowns.
4. **Save your Home** by tapping the house icon next to your accommodation.
5. The next departure and a live countdown will appear instantly!

*(Secret: Triple-tap the clock for a fun surprise!)*

### Install on your phone (recommended)

**iOS (Safari):** Tap **Share** → **Add to Home Screen**  
**Android (Chrome):** Tap the menu → **Add to Home Screen**

Once installed, Etihad Bus opens fullscreen like a native app.

---

## Tech

- Single `index.html` file — no build step, no server
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Lucide Icons](https://lucide.dev/) for icons
- All schedule data is embedded in the page
- **Geolocation API** for smart proximity detection
- **Service Workers** for 100% offline PWA capabilities
- `localStorage` for persisting user preferences

---

<div align="center">

Made for crew, by crew.

</div>
