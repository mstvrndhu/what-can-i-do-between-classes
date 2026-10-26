# What can I do between classes? (課間我想做什麼？) · AI Campus Companion v2.0

> **Introduction to Artificial Intelligence Midterm Project**  
> An intelligent, context-aware campus companion designed to help university students optimize break intervals through 4-phase circadian heuristics, Multi-Attribute Utility Theory (MAUT), hardware-accelerated celestial physics, and ambient sensory relaxation.

---

## 🚀 Live Demo & Links
* **Live Website (GitHub Pages)**: [https://mstvrndhu.github.io/what-can-i-do-between-classes/](https://mstvrndhu.github.io/what-can-i-do-between-classes/)
* **GitHub Repository**: [https://github.com/mstvrndhu/what-can-i-do-between-classes](https://github.com/mstvrndhu/what-can-i-do-between-classes)
* **Releases**:
  * [v2.0 Release](https://github.com/mstvrndhu/what-can-i-do-between-classes/releases/tag/v2.0)
  * [v1.0 Release](https://github.com/mstvrndhu/what-can-i-do-between-classes/releases/tag/v1.0)

---

## 🌟 What's New in v2.0

### 1. 🌌 Dynamic Celestial Sky Arc & Atmosphere
* **Zero Performance Overhead**: Hardware-accelerated with pure CSS transforms and SVG vectors (0% idle CPU usage).
* **Real-Time Sun & Moon Trajectory**:
  * Daytime (06:00–18:00): Glowing sun rises from the East (bottom-left), arcs across the zenith at noon, and sets in the West.
  * Nighttime (18:00–06:00): Soft crescent moon rises from the East, crosses the night sky, and sets at dawn.
* **Atmospheric Sky Shifts**: Smooth gradient transitions between Dawn, Midday, Golden Hour/Sunset, and Starry Midnight.

### 2. ⚙️ Settings Modal & 3-Mode Theme System
* **Real-Time Circadian Sync**: Automatically displays crisp Light Mode during daylight and shifts to deep Dark Mode at night.
* **System OS**: Synchronizes with your device's native dark/light preference.
* **Manual Override**: Toggle and lock Light or Dark mode.

### 3. 🕒 Interactive AI Time Simulator (Presentation Mode)
* Located inside the Settings modal: 1-click preview of `Live Clock`, `Morning (09:00)`, `Noon (13:00)`, `Sunset (17:30)`, or `Midnight (00:30)`.
* Instantly moves celestial bodies, shifts atmospheric colors, and re-evaluates AI utility recommendations for classroom demonstration.

### 4. 🎵 Synthesized Web Audio Campus Soundscapes
* Zero-dependency audio synthesizer:
  * 🌧️ Gentle Rain (low-pass filtered white noise)
  * 🧘 Lo-Fi Binaural Hum (6Hz theta relaxation wave)
  * 💨 Focus White Noise (bandpass concentration baseline)
* Plays automatically during break timer countdowns or via HUD toggle.

### 5. 📊 Student Break Analytics Dashboard
* Live counters tracking **Minutes Recharged**, **Breaks Completed**, and **Favorite Category Breakdown**.

---

## 🧠 Artificial Intelligence System

### Multi-Attribute Utility Theory (MAUT) Decision Function
$$U(a) = w_{fit} \cdot u_{fit}(a) + w_{circadian} \cdot u_{circadian}(a) + w_{goal} \cdot u_{goal}(a) - \text{penalty}_{novelty}(a) + w_{bandit} \cdot r(a)$$

* **4-Phase Circadian Cycle**:
  1. **Morning Focus (06:00–11:59)**: Study setup, active recall flashcards, and organization.
  2. **Afternoon Recharge (12:00–17:59)**: Campus walks and stair climbs to banish post-lunch drowsiness.
  3. **Evening Review (18:00–21:59)**: Planning tomorrow, coursework review, and quiet reading.
  4. **Late Night Reset (22:00–05:59)**: Eye-rest breaks, 4-7-8 breathing, and Lo-Fi relaxation.
* **Multi-Armed Bandit**: User ratings (👍 / 👎) update reinforcement weights locally.
* **Explainable AI (XAI)**: Transparent reasoning tags and match percentages.

---

## 📂 Project Structure

```text
├── index.html         # Complete single-page application (HTML, CSS, JS)
├── activities.json    # Catalog of 20 enriched campus activities
└── README.md          # Comprehensive documentation
```

---

## 🏃 How to Run Locally

### Option 1: Direct File Launch
Double-click `index.html` to open in any web browser.

### Option 2: Local Web Server
```bash
python -m http.server 8000
```
Open [http://localhost:8000](http://localhost:8000) in your browser.
