# 🎮 Wintensity — Winrate Calculator & Grind Timer

A lightweight, web-based tool built for gamers who want to **track winrate goals and manage grind sessions with precision**.

Built with **HTML, CSS, and JavaScript** — fast, responsive, and fully offline-ready.

---

## 🚀 Live Demo

* 🌐 Try it here: **[https://wintensity.netlify.app/](https://wintensity.netlify.app/)**

---

## 🚀 Features

### 🧮 Winrate Calculator

* Input current winrate, total matches, and desired winrate
* Instantly calculates:

  * 🔢 Wins needed to reach your goal
  * 📉 Winrate impact after a loss
* Real-time calculation with input validation
* Clean and responsive UI

---

### ⏳ Grind Timer

* Custom countdown timer (hours, minutes, seconds)
* Full controls: Start, Pause, Stop, Reset
* 📊 Visual progress bar
* 🔊 Sound alert when timer ends
* Runs even when tab is minimized

---

## 💻 Technical Highlights

* Single-page web app (no dependencies)
* Built with **pure HTML, CSS, JavaScript**
* Modern dark UI with smooth animations
* Fully responsive design (mobile + desktop)
* Web Audio API for alert sounds
* Accurate timer system using JavaScript Date handling

---

## 🧱 Project Files

### `index.html`

* Main structure of the application
* Contains Winrate Calculator and Grind Timer UI

### `styles.css`

* Dark modern UI styling
* Responsive layout, animations, and gradients

### `script.js`

* Winrate calculation logic
* Timer system (start, pause, reset, countdown handling)
* UI interactions and validation

---

## 📝 Usage

### For Users

* Open the live demo link
* Use the **Winrate Calculator** to compute required wins
* Set the **Grind Timer** for focused gaming sessions
* Track progress and improve consistency

### For Developers

#### 🎨 Customize Theme

```css id="wntz2a"
:root {
  --primary-color: #6c5ce7;
  --background-color: #0f0f1a;
  --accent-color: #00d1ff;
}
```

#### ⚙️ Modify Logic

* Winrate system → `script.js`
* Timer system → `script.js`
* UI layout → `index.html`
* Styling → `styles.css`

#### 🔊 Audio Alert

* Uses Web Audio API
* Can be replaced with custom sound file

---

## 🌐 Browser Support

| Browser | Support |
| ------- | ------- |
| Chrome  | ✅ Full  |
| Firefox | ✅ Full  |
| Edge    | ✅ Full  |
| Safari  | ✅ Full  |
| Opera   | ✅ Full  |

---

## 📌 To-Do / Future Improvements

* Add ranked game presets (LoL, Valorant, ML, etc.)
* Save session history using localStorage
* Add streak tracking system
* Convert into installable PWA
* Export winrate stats as CSV
* Improve mobile UX further

---

## 👤 Author

**GDX**
