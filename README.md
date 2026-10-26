# What can I do between classes? (下課可以做什麼？)

> **Live Webpage**: [https://mstvrndhu.github.io/what-can-i-do-between-classes/](https://mstvrndhu.github.io/what-can-i-do-between-classes/)  
> **Release**: `v3.0` (Production Grade)

---

## What is this?

A modern, intelligent, and lightweight campus companion designed to help university students optimize breaks between lectures. It calculates upcoming schedule gaps, matches energy levels, suggests contextual recharge activities, and tracks well-being analytics—all running 100% locally in your browser with zero external dependencies.

---

## Key Features in v3.0

### 1. Zero-Flash & Anti-Jitter Theme Architecture
- **Black Baseline Canvas**: Default canvas starts at `#090d16` (dark mode baseline), completely eliminating any white flash when switching between dark themes or reloading the page late at night.
- **Early-Execution Head Engine**: Executes theme preferences immediately prior to the first render pass, preventing layout jumps (e.g. top padding shifting on reload in static mode).
- **Dynamic Mode**: Continuous atmospheric circadian lighting (Morning, Afternoon, Sunset, Night) with a revolving parabolic celestial arc (Sun & Moon) synchronized to the device clock.
- **Static Mode**: Minimalist, high-contrast, non-animated appearance supporting System OS, Light, and Dark modes.

### 2. Class Timetable & Real-Time Break Gap Engine
- **Live Timetable Gap Detection**: Displays real-time status banner indicating current course or the exact time remaining until your next class.
- **Auto-Sync Mode**: Automatically aligns the break time filter (`10m`, `15m`, `30m`, `60m`) with your actual remaining gap.
- **Customizable Courses**: Add, edit, or remove your daily courses with room numbers and class schedules, or load the pre-configured sample university timetable.

### 3. 1-Click JSON Backup & Restore System
- **1-Click Export**: Download your full campus companion profile (`campus-companion-backup.json`) including courses, custom activities, recharge history, ratings, and AI weights.
- **1-Click Restore**: Use standard HTML5 `FileReader` to restore and load your data on any device or fresh browser installation without needing a database server.

### 4. Custom Activity Creator & Enhanced Catalog
- **Create Your Own Breaks**: Add personalized activities with custom emoji, duration, location, category, and action steps.
- **Searchable Catalog**: Instant keyword search across both core and custom activities.

### 5. Post-Break Reflection & Analytics
- **5-Star Reflection Modal**: Rate each completed session and tag your recharge feeling (*Energized ⚡*, *Relaxed 🌿*, *Focused 💻*, *Ready for Class ✨*).
- **Student Dashboard**: Live tracking of total recharged minutes, completed sessions, and favorite categories.

### 6. Ambient Synthesized Soundscapes
- Built with pure Web Audio API (Rain, Lo-Fi Binaural Hum, Focus White Noise) with smooth `1.8s` exponential fade-in and `1.2s` fade-out transitions.

### 7. Bilingual Experience
- Seamless toggle between **English** and **Traditional Chinese (Taiwan usage)**.

---

## Technical Specifications
- **Stack**: Vanilla HTML5, CSS3, Modern JavaScript (ES6+).
- **Dependencies**: None (0 external libraries, 0 CDN calls, completely offline-first).
- **Storage**: Browser `localStorage` with JSON export/import.
- **Audio**: Web Audio API (real-time procedural audio synthesis).
- **Hosting**: GitHub Pages via `main` branch.
