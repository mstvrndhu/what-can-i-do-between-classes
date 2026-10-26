# What can I do between classes? (課間我想做什麼？) · AI Campus Companion

> **Introduction to Artificial Intelligence Midterm Project**  
> An intelligent, context-aware decision system designed to help college students optimize their breaks between lectures through Multi-Attribute Utility Theory (MAUT), circadian heuristics, and reinforcement preference learning.

---

## 🚀 Live Demo & Repository
* **Live Website (GitHub Pages)**: [https://mstvrndhu.github.io/what-can-i-do-between-classes/](https://mstvrndhu.github.io/what-can-i-do-between-classes/)
* **GitHub Repository**: [https://github.com/mstvrndhu/what-can-i-do-between-classes](https://github.com/mstvrndhu/what-can-i-do-between-classes)

---

## 🧠 Artificial Intelligence System (v1.0)

### 1. Multi-Attribute Utility Theory (MAUT) Decision Model
Rather than simple uniform random picking, the engine evaluates each candidate activity $a$ across multiple weighted criteria:
$$U(a) = w_{fit} \cdot u_{fit}(a) + w_{circadian} \cdot u_{circadian}(a) + w_{goal} \cdot u_{goal}(a) - \text{penalty}_{novelty}(a) + w_{bandit} \cdot r(a)$$

* **Duration Fit Utility ($u_{fit}$)**: Maximizes effective utilization of available time (10m, 15m, 30m, 60m) while incorporating transition buffers for returning to class on time.
* **Circadian / Time-of-Day Context ($u_{circadian}$)**: Real-time clock detection dynamically shifts scoring:
  * **Morning (06:00–12:00)**: Prioritizes active recall, desk organization, and gentle focus setup.
  * **Afternoon (12:00–17:00)**: Mitigates post-lunch fatigue by boosting physical movement, brisk walks, and mindfulness breaks.
  * **Evening (17:00–23:00)**: Prioritizes wind-down, task planning, and club brainstorming.
* **Goal Orientation ($u_{goal}$)**: Students can guide AI focus across 4 modalities: *Mental Reset* 🌿, *Study & Focus* 💻, *Physical Refresh* 🏃, and *Creative & Social* 🎨.
* **Anti-Fatigue / Novelty Filter**: Consecutive repeat penalties prevent recommendation stagnation.
* **Multi-Armed Bandit Preference Learning**: Upvotes (👍) and downvotes (👎) update reinforcement weights in `localStorage`, personalizing recommendations over time.
* **Explainable AI (XAI)**: Displays real-time reasoning tags and match percentages so students understand *why* an activity was recommended.

---

## ✨ Features & Upgrades

* ⏱️ **Integrated Break Countdown Timer**: Pomodoro-style visual timer with pause/resume and zero-dependency Web Audio synthesised chimes.
* 📚 **Activity Catalog Drawer**: Explore and search all 20 campus activities with live keyword filtering.
* 🌓 **Dark / Light Mode**: Seamless theme switching with system preference auto-detection.
* 🌐 **Full Bilingual Support (i18n)**: One-click switch between English and Traditional Chinese (繁體中文台灣用語).
* 💾 **Persistent Session Storage**: History log, theme, and learned AI preference weights persist across browser restarts.
* 📱 **Mobile & Desktop Responsive**: Modern clean campus card interface.

---

## 📂 Project Structure

```text
├── index.html         # Complete single-page application (HTML, CSS, JS)
├── activities.json    # Catalog of 20 enriched activities with AI metadata
└── README.md          # Project documentation
```

---

## 🏃 How to Run Locally

### Option 1: Direct File Launch
Double-click `index.html` to open it immediately in any browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local Web Server
```bash
python -m http.server 8000
```
Open [http://localhost:8000](http://localhost:8000) in your browser.
