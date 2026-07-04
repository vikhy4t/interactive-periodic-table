# 🧪 Interactive 3D Periodic Table

<p align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Anime.js](https://img.shields.io/badge/Anime.js-Animation-ff2d55?style=for-the-badge)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Hands-0097A7?style=for-the-badge)
![Responsive](https://img.shields.io/badge/Responsive-Desktop-success?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open%20Source-❤-blueviolet?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

<p align="center">
An immersive <b>3D Periodic Table</b> built with pure HTML, CSS and JavaScript. Experience chemistry through animated spatial layouts, real‑time hand gesture interaction, and smooth transitions powered by Anime.js.
</p>

<p align="center">

<a href="https://periodic-table-07.netlify.app" target="_blank">
  <img src="https://img.shields.io/badge/🌐%20Live%20Demo-Visit%20on%20Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Live Demo on Netlify">
</a>

</p>


---

# ✨ Highlights

- 🧪 Complete interactive periodic table.
- 🌍 Four visualization modes:
  - Table
  - Sphere
  - Helix
  - Grid
- 🤚 Hand gesture navigation using MediaPipe Hands.
- 🎥 Live webcam tracking.
- 🖱️ Interactive mouse-controlled camera.
- ⚡ Smooth spring animations with Anime.js.
- 📖 Expandable cards with scientific information.
- 🎨 Modern dark UI with color-coded element categories.
- 🚀 No build tools required — just open the HTML file.

---

# 📸 Screenshots

| Table | Sphere |
|-------|--------|
| ![](assets/screenshots/table.png) | ![](assets/screenshots/sphere.png) |

| Helix | Grid |
|-------|------|
| ![](assets/screenshots/helix.png) | ![](assets/screenshots/grid.png) |

---

# 🎮 Controls

| Action | Result |
|---------|--------|
| 🖱️ Move Mouse | Rotate the 3D scene |
| 👆 Click Element | Expand element information |
| 🤏 Pinch Gesture | Cycle between layouts |
| ⌨️ ESC | Close expanded card |

---

# 🏗️ Architecture

```text
User
 │
 ├── Mouse Input
 └── Webcam
        │
        ▼
 MediaPipe Hands
        │
 Gesture Detection
        │
        ▼
 Animation Controller
        │
        ▼
 Anime.js Layout Engine
        │
        ▼
 3D Periodic Table
```

---

# 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript (ES6 Modules)
- Anime.js
- Google MediaPipe Hands
- Camera Utils
- Drawing Utils

---

# ⚙️ Installation

```bash
git clone https://github.com/vikhy4t/interactive-periodic-table.git
cd interactive-periodic-table
```

Open `periodictable.html` (or your renamed `index.html`) in a modern Chromium-based browser and allow camera access to enable gesture controls.

---

# 📁 Project Structure

```text
Interactive-3D-Periodic-Table
│
├── periodictable.html
├── README.md
├── LICENSE
├── .gitignore
│
└── assets/
    └── screenshots/
        ├── table.png
        ├── sphere.png
        ├── helix.png
        └── grid.png
```


---

# 🚀 Roadmap

- [ ] Mobile gesture optimization
- [ ] Search and filter elements
- [ ] Element categories legend
- [ ] AR/VR exploration mode
- [ ] Educational quiz mode
- [ ] Audio feedback & accessibility improvements

---

# 🙏 Credits & Acknowledgements

This project was made possible by several incredible open-source projects.

### Libraries

- **Anime.js** — Powers the layout transitions, spring animations and motion system.
- **Google MediaPipe Hands** — Real-time hand tracking and gesture recognition.
- **MediaPipe Camera Utils** — Webcam capture utilities.
- **MediaPipe Drawing Utils** — Hand landmark rendering.

### Attribution

This project integrates and extends these technologies with custom interaction logic, interface refinements, gesture-based layout switching, styling, UI enhancements, and project integration by **Vikhyat**.

If you build upon this project, please consider keeping the acknowledgements and supporting the original open-source libraries.

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Vikhyat**

- GitHub: https://github.com/vikhy4t
- Instagram: https://instagram.com/vikhy4t
- X (Twitter): https://x.com/vikhy4t

---

<p align="center">
If you enjoyed this project, consider giving it a ⭐ on GitHub.
</p>
