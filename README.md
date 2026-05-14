# 🎮 Ta6aboq (تطابق): Shape Matcher | لعبة الأشكال

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Status](https://img.shields.io/badge/Status-Innovation_Success-brightgreen)

A fast-paced, space-themed educational game where players must identify matching shapes under pressure. 

---

## 🚀 The Backstory
This project was developed in **less than 35 minutes** as an experimental introduction to AI for an 8th-grade innovator. 

* **Ideation:** My brother explained his ideas using **Speech-to-Text**.
* **Execution:** AI (Claude) translated those spoken thoughts into clean, functional code.
* **Result:** A fully working game that turned a kid's "what if" into "here it is."

---

## 🧠 Game Features

### 1. Dynamic HUD & Pressure
* **Question Tracking:** 10 rounds per game to keep it engaging.
* **The 5-Second Rule:** A shrinking, color-changing timer bar to increase excitement.
* **Live Scoring:** Immediate point updates for every correct match.

### 2. Visual Logic
* **Animated Feedback:** `Pulse` effect for correct answers and `Shake` effect for mistakes.
* **Progress Bar:** A row of 10 dots tracking your success/failure in real-time.

### 3. Procedural Design
* **Smart Shuffling:** Shapes and colors are randomized every round.
* **Deep Space Theme:** A dark, glowing UI with an animated starfield background.

---

## 🛠️ Technical Stack

| Component | Technology |
| :--- | :--- |
| **Logic** | Vanilla JavaScript (ES6+) |
| **Styling** | CSS3 (Flexbox, Grid, Keyframes) |
| **Graphics** | Dynamic SVG Pathing |
| **Fonts** | Google Fonts (Tajawal) |

---

## 🕹️ How to Play

1.  **Observe:** Look at the grid of **9 dark shapes** at the top.
2.  **Match:** Find the matching shape among the **4 bright choices** at the bottom.
3.  **Be Quick:** Click before the timer hits zero!
4.  **Score:** Aim for a 10/10 to prove your focus!

---

## 🔧 Technical Highlight: The "Crescent Moon" Fix
During development, we solved a classic SVG rendering challenge. Standard arcs were failing to render properly, so we implemented a **Bézier Curve path** to ensure the crescent appeared perfectly across all browsers:

```javascript
// High-compatibility Crescent Path
d="M22 2C10.95 2 2 10.95 2 22s8.95 20 20 20c1.8 0 3.53-.24 5.18-.68-7.5-3.15-12.8-10.58-12.8-19.32S19.7 7.83 27.2 4.68A19.86 19.86 0 0 0 22 2z"
```

## 📈 The Lesson
This project proves that Language is the new Programming Language. By focusing on clear communication, an 8th grader built a functional app in the time it takes to eat lunch.

**Created with ❤️ and AI to empower the next generation of innovators.**
