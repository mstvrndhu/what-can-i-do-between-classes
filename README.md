# What can I do between classes? (課間我想做什麼？) · Smart Campus Companion v2.1

> A modern, context-aware web companion designed to help students optimize break intervals through 4-phase circadian heuristics, smooth revolving celestial physics, synthesized ambient audio, and responsive environmental lighting.

---

## 🚀 Live Demo & Links
* **Live Web App (GitHub Pages)**: [https://mstvrndhu.github.io/what-can-i-do-between-classes/](https://mstvrndhu.github.io/what-can-i-do-between-classes/)
* **GitHub Repository**: [https://github.com/mstvrndhu/what-can-i-do-between-classes](https://github.com/mstvrndhu/what-can-i-do-between-classes)
* **Releases**:
  * [v2.1 Release](https://github.com/mstvrndhu/what-can-i-do-between-classes/releases/tag/v2.1)
  * [v2.0 Release](https://github.com/mstvrndhu/what-can-i-do-between-classes/releases/tag/v2.0)
  * [v1.0 Release](https://github.com/mstvrndhu/what-can-i-do-between-classes/releases/tag/v1.0)

---

## 🌟 What's New in v2.1

### 1. 🌌 Decoupled Theme System (Dynamic vs Static)
* **Dynamic Theme (Default)**:
  * Environmental circadian lighting that softly tints cards and backgrounds to match the mood of Morning, Afternoon, Evening, and Night.
  * Live or custom time cycle selector (`Live Clock`, `Morning`, `Afternoon`, `Evening`, `Night`).
* **Static Theme**:
  * Clean, non-animated classic modes (`System OS`, `Light`, `Dark`).

### 2. ☀️ Continuous Clockwise Celestial Revolution
* **Unobstructed View**: Generous top sky clearance so the revolving Sun and Moon glide cleanly above content without being blocked by headers or glass blur.
* **Exact Solar Math**: Continuous parabolic arc synced to current hour and minute (e.g. 14:36, 18:29, 01:30).
* **Radiance Pulses**: Glowing sun corona and soft lunar halo breathing animations.

### 3. 🎵 Smooth Audio Fading & HUD Equalizer
* **Exponential Fade In/Out**: Web Audio API gain ramps smoothly over 1.8 seconds when starting and 1.2 seconds when stopping for zero clicks or pops.
* **Live Equalizer**: Interactive bouncing audio bars in the top status pill during playback.

### 4. 🧠 Circadian Recommendation Engine
* Evaluates duration fit, energy requirements, and circadian context across 20 structured campus activities with transparent reasoning badges.

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
