# What can I do between classes? (課間我想做什麼？)

A lightweight web application that helps university and college students quickly select suitable activities during breaks between classes based on their location, available time, and energy level.

---

## 🌟 Features

* **Multi-Factor Filtering**:
  * **Location**: All, Indoor, or Outdoor
  * **Available Time**: 15 minutes, 30 minutes, or 60 minutes
  * **Energy Level**: All, Low, or Medium
* **Smart Activity Picking**: Randomly selects an activity matching the selected criteria.
* **History Tracking**: Keeps a running log of the last 5 successful picks.
* **Bilingual Support (i18n)**: Instant one-click toggle between English and Traditional Chinese (繁體中文).
* **Reset & Clear**: One-click reset for filters and history.
* **Zero Dependencies**: Pure HTML5, CSS3, and vanilla JavaScript in a single lightweight package.

---

## 📂 Project Structure

```text
├── index.html         # Main web application (HTML, CSS, JS)
├── activities.json    # JSON database of activities
└── README.md          # Project documentation
```

---

## 🚀 How to Run Locally

### Option 1: Direct File Launch
Double-click `index.html` to open it in your default web browser (Edge, Chrome, Firefox, Safari).

### Option 2: Local Web Server
Using Python:
```bash
python -m http.server 8000
```
Then navigate to [http://localhost:8000](http://localhost:8000) in your browser.
