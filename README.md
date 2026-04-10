# 🌊 Aqua Project

<div align="center">

![Aqua Project](https://img.shields.io/badge/Aqua-Project-8B5CF6?style=for-the-badge&logo=water&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**A Modern Responsive Landing Page with Smooth Scroll Animations**

[🔗 Live Demo](https://dvdr6.github.io/aqua-project.github.io/) • [📁 Repository](https://github.com/dvdr6/aqua-project.github.io)

</div>

---

## 📋 Overview

Aqua Project is a clean, modern landing page featuring smooth scroll animations, responsive design, and interactive navigation. Built with vanilla HTML, CSS, and JavaScript.

---

## ✨ Features

- 🎯 **Sticky Navigation** - Header stays visible while scrolling
- 📱 **Responsive Design** - Mobile-first hamburger menu
- ✨ **Scroll Animations** - Powered by ScrollReveal.js
- 🎨 **Modern UI** - Clean purple-themed design
- ⚡ **Lightweight** - No heavy frameworks

---

## 🛠 Tech Stack

```
HTML5  →  Structure
CSS3   →  Styling & Layouts
JS ES6 →  Interactivity
ScrollReveal.js → Animations
```

---

## 📂 Project Structure

```
aqua-project.github.io/
│
├── index.html    # Main HTML file
├── style.css     # Styles & animations
├── script.js     # JavaScript logic
└── images/       # Image assets
```

---

## 🎬 Key Components

### 1. **Sticky Header**
```javascript
window.addEventListener("scroll", function() {
    var header = document.querySelector("header");
    header.classList.toggle("sticky", window.scrollY > 0);
});
```

### 2. **Mobile Menu Toggle**
```javascript
function toggleMenu() {
    var menuToggle = document.querySelector(".menuToggle");
    var navigation = document.querySelector(".navigation");
    menuToggle.classList.toggle("active");
    navigation.classList.toggle("active");
}
```

### 3. **ScrollReveal Animations**
```javascript
ScrollReveal().reveal('#banner', {
    delay: 500,
    origin: 'bottom',
    distance: '60px'
});
```

---

## 🎨 Color Scheme

| Color | Hex | Usage |
|-------|-----|-------|
| 🟣 Purple | `#8B5CF6` | Primary accent |
| ⬜ White | `#FFFFFF` | Backgrounds |
| ⬛ Dark | `#111111` | Text |

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/dvdr6/aqua-project.github.io.git

# Open index.html in your browser
```

**No build process required!** Just open `index.html` in any modern browser.

---

## 📱 Responsive Breakpoints

| Device | Behavior |
|--------|----------|
| Desktop | Full navigation bar |
| Tablet | Adjusted spacing |
| Mobile | Hamburger menu |

---

## 🌐 Browser Support

✅ Chrome 90+ • ✅ Firefox 88+ • ✅ Safari 14+ • ✅ Edge 90+

---

## 📦 Dependencies

- [ScrollReveal.js](https://scrollrevealjs.org/) - Scroll animations library

```html
<script src="https://unpkg.com/scrollreveal"></script>
```

---

## 👨‍💻 Author

**GitHub:** [@dvdr6](https://github.com/dvdr6)

---

<div align="center">

### Made with 💜

**Simple • Clean • Responsive**

[⬆ Back to Top](#-aqua-project)

</div>
