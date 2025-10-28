# 🎮 EmojiCrush Console  
**URL:** [rajatkumar1.me/EmojiCrush](https://rajatkumar1.me/EmojiCrush)

---

## 🧩 Project Overview  

**EmojiCrush Console** is a static, single-page web application that reimagines the classic **match-3** game as a **futuristic, high-tech console**.  
It is designed to be visually *unrealistic* and sleek, prioritizing aesthetics and a unique user experience through a combination of modern web technologies.  

The entire application is **self-contained in a single HTML file**, showcasing robust front-end development **without any backend dependencies**.

---

## ✨ Key Features  

### 🧊 Sleek Glassmorphism UI  
- Semi-transparent panels with **backdrop blur** and **glowing borders** create a “floating glass” effect.  
- The main console visually hovers over an animated background.

### 🌌 Dynamic Particle Background  
- Uses **tsparticles** to generate a complex, interactive network of moving particles.  
- Gives the page a *live* and *futuristic* atmosphere.

### 🎵 Generative Audio  
- Integrates **Tone.js** for **real-time synth-based sound effects** (swap, match, invalid move).  
- Eliminates static audio files for a pure console-like experience.

### 📱 Fully Responsive Design  
- Built with **Tailwind CSS**, `clamp()`, and `vmin` units for fluid scaling.  
- Perfectly adapts across all screen sizes — mobile to desktop — with **no scrollbars**.

### 🧠 Robust Game Logic  
Written entirely in **pure JavaScript (ES6+)**, the logic handles:
- Grid generation with no initial matches.  
- Player input, gem selection, and swapping.  
- Validation for adjacent-only swaps.  
- Match detection (horizontal & vertical).  
- Cascading matches and chain reactions.  
- “Gravity” physics for falling gems.  
- Automatic refilling of the board.  
- Score tracking, move limits, and game-over modal.

### 🚀 High-Tech Theming  
- Uses the **Orbitron** Google Font for a consistent sci-fi console aesthetic.  

### 🌀 Animated Transitions  
- Smooth **CSS keyframe animations** for swaps, matches, and new gem entries.  
- Ensures polished, visually engaging gameplay.

---

## 🧰 Technology Stack  

| Technology | Purpose |
|-------------|----------|
| **HTML5** | Structural foundation of the app |
| **Tailwind CSS (CDN)** | Styling, layout, responsiveness |
| **JavaScript (ES6+)** | Game logic, state management, DOM manipulation |
| **tsparticles (CDN)** | Animated particle background |
| **Tone.js (CDN)** | Real-time sound generation |

---

*EmojiCrush Console* is not just a game — it’s a **demonstration of front-end power**, visual design, and creative coding in one file.
