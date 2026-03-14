<div align="center">

# Shajalal Hossain
### Freelance Web Developer · Rangpur, Bangladesh

[![Portfolio](https://img.shields.io/badge/Portfolio-Live-c9a84c?style=for-the-badge&logo=google-chrome&logoColor=white)](https://shajalalhossain.github.io/portfolio)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shajalal@email.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shajalalhossain)

<br/>

> *"Building digital experiences through code and design."*

<br/>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Framer](https://img.shields.io/badge/Framer-0055FF?style=flat-square&logo=framer&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 📌 About This Project

This is my **personal portfolio website** — designed and developed from scratch using pure **HTML5, CSS3, and JavaScript**. No frameworks, no dependencies. Just clean, handcrafted code.

The design is inspired by modern agency templates (Fade - Framer) and adapted into a fully custom, hand-coded implementation. Every animation, layout, and interaction was built manually.

**Live URL:** `https://shajalalhossain.github.io/portfolio`

---

## 🧑‍💻 About Me

I am **Shajalal Hossain**, a 23-year-old freelance web developer based in Rangpur, Bangladesh. I have been building websites professionally for over **2 years**, working with clients from around the world through **Fiverr** and direct collaborations.

| | |
|---|---|
| 📍 **Location** | Rangpur, Bangladesh |
| 🎂 **Age** | 23 years |
| 💼 **Experience** | 2+ Years (Freelance) |
| 🌐 **Websites Built** | 130+ |
| 🤝 **Client Projects** | 30+ |
| 🔁 **Clone Projects** | 18+ |
| 🕒 **Availability** | Open to Work — Remote / Freelance |

---

## 🛠️ Technical Skills

### Frontend Development
| Technology | Level |
|---|---|
| HTML5 (Semantic) | ████████████ Advanced |
| CSS3 (Flexbox, Grid, Animations) | ████████████ Advanced |
| Tailwind CSS | ██████████░░ Advanced |
| JavaScript (DOM, Events, APIs) | ████████░░░░ Intermediate |

### WordPress Development
| Technology | Level |
|---|---|
| Elementor Page Builder | ████████████ Expert — 70+ sites |
| Theme Customization | ████████████ Expert |
| Plugin Management | ████████████ Expert |
| WooCommerce | ██████████░░ Advanced |
| WordPress Dashboard | ████████████ Expert |

### Design & Tools
| Tool | Usage |
|---|---|
| Figma | UI Design → Website Conversion |
| Framer | Animated Website Building |
| Git & GitHub | Version Control |
| Adobe Photoshop | Basic Image Editing |

### Currently Learning
```
PHP  ·  Laravel  ·  React.js
```

---

## 🚀 Services I Offer

```
01  WordPress Website Development     Elementor · WooCommerce · Custom Themes
02  Website Cloning & Replication     Pixel-Perfect · 18+ Projects Delivered
03  Figma to Website Conversion       HTML/CSS · Tailwind · Responsive
04  Framer Website Design             Animated · Modern · No-Code
05  Landing Page Design               Conversion Focused · SEO Ready
06  AI-Assisted Web Development       Faster Delivery · Quality Code
```

---

## 💻 This Portfolio — Technical Overview

### Architecture
```
portfolio/
│
├── final.html              ← Main single-file portfolio (All-in-one)
│   ├── <style>             ← All CSS
│   └── <script>            ← All JavaScript
├── index.html              ← Lightweight redirect to final.html
├── .github/workflows/deploy.yml ← Auto-deploy workflow for GitHub Pages
└── README.md               ← This file
```

### What's Inside `index.html`

```
Sections
├── Navigation              Fixed nav + Mobile hamburger menu
├── Hero Section            Animated photo + orbiting shapes + ticker
├── Process                 3-step work process (2-column layout)
├── Services                6 service cards with hover animations
├── Projects                4 featured project cards
├── Skills Marquee          Dual infinite scroll skill strips
├── About                   Bio + experience timeline
├── Testimonials            3 client review cards
├── FAQ                     Accordion-style FAQ
├── Contact CTA             Call-to-action section
└── Footer                  Links + copyright
```

### Key Technical Implementations

**Custom Cursor**
```javascript
// Smooth lagging cursor with scale-on-hover
const cur = document.getElementById("cur");
document.addEventListener("mousemove", e => {
  cur.style.left = e.clientX + "px";
  cur.style.top  = e.clientY + "px";
});
```

**Scroll Reveal (IntersectionObserver)**
```javascript
const obs = new IntersectionObserver((entries) => {
  entries.forEach((e, i) => {
    if (e.isIntersecting) {
      setTimeout(() => e.target.classList.add("on"), i * 70);
    }
  });
}, { threshold: 0.08 });
```

**Infinite Orbiting Animation (CSS)**
```css
@keyframes orbit {
  from { transform: rotate(0deg) translateX(120px) rotate(0deg); }
  to   { transform: rotate(360deg) translateX(120px) rotate(-360deg); }
}
.orb1 { animation: orbit 6s linear infinite; }
```

**Marquee (Infinite Scroll)**
```css
@keyframes marquee {
  from { transform: translateX(0); }
  to   { transform: translateX(-50%); }
}
```

---

## 🎨 Design System

### Typography
| Role | Font | Weight |
|---|---|---|
| Headings | Cinzel Decorative | 400 / 700 / 900 |
| Body Text | Open Sans | 300 / 400 / 600 / 700 |

### Color Palette
```
Background    #0a0a0a    ████  Primary dark
Surface       #111111    ████  Cards, panels
Accent        #c9a84c    ████  Gold — CTA, highlights
Text          #ffffff    ████  Primary text
Muted         #ffffff42  ████  Secondary text
Border        #ffffff08  ████  Dividers, lines
```

### Layout
```
Max Width     : 1140px
Padding       : 40px (desktop) · 20px (mobile)
Grid System   : CSS Grid — 2-column sections
Breakpoint    : 900px (mobile)
```

---

## 🌀 Animation Reference

| Name | Duration | Type | Applied To |
|---|---|---|---|
| `imgFloat` | 5s | ease-in-out infinite | Profile photo |
| `orbit` | 6s | linear infinite | Dot 1 |
| `orbit2` | 9s | linear infinite | Dot 2 |
| `orbit3` | 12s | linear infinite | Dot 3 |
| `pulseRing` | 4s | ease-in-out infinite | Ring 1 |
| `pulseRing2` | 5s | ease-in-out infinite | Ring 2 |
| `spinSlow` | 25s | linear infinite | Ring 3 |
| `shimmer` | 4s | linear infinite | Hero heading |
| `glowPulse` | 4s | ease-in-out infinite | Background glow |
| `marquee` | 22–28s | linear infinite | Skill strips |
| `fadeUp` | 0.9s | cubic-bezier | Page load |
| `lineGrow` | 3s | ease-in-out infinite | Decorative line |

---

## 📱 Responsive Design

```
Desktop (1140px+)   Full 2-column layout · Custom cursor · All animations
Tablet  (900-1140)  Adjusted grid · Reduced padding
Mobile  (<900px)    Single column · Hamburger menu · Touch friendly
```

**Mobile Menu Features:**
- Hamburger → X toggle animation
- Full-screen overlay menu
- Body scroll locked when open
- Auto-closes on link click or scroll

---

## ⚙️ Getting Started

### Option 1 — Direct Open
```bash
# Download or clone this repo
git clone https://github.com/shajalalhossain/portfolio.git

# Open in browser (no server needed)
open index.html
```

### Option 2 — Local Server
```bash
# Using VS Code Live Server extension
# OR using Python
python3 -m http.server 8000

# Then visit
http://localhost:8000
```

### Option 3 — Deploy to GitHub Pages (Automatic)
```bash
# Push this repository to GitHub (main branch)
git init
git add .
git commit -m "feat: initial portfolio"
git remote add origin https://github.com/USERNAME/portfolio.git
git push -u origin main
```

The included GitHub Actions workflow (`.github/workflows/deploy.yml`) automatically deploys `final.html` as `index.html` on GitHub Pages after each push to `main`.

```text
GitHub → Settings → Pages → Build and deployment: GitHub Actions
Live URL: https://USERNAME.github.io/portfolio
```

---

## 📊 Performance

| Metric | Status |
|---|---|
| External Dependencies | Zero (only Google Fonts) |
| Build Tools Required | None |
| JavaScript Libraries | None |
| File Count | 1 HTML file |
| Browser Support | Chrome, Firefox, Safari, Edge |

---

## 📬 Contact & Hire Me

I am currently **open to work** — freelance projects, remote positions, and full-time opportunities.

| Platform | Details |
|---|---|
| 📧 **Email** | shajalal@email.com |
| 💼 **Fiverr** | fiverr.com/shajalalhossain |
| 🐙 **GitHub** | github.com/shajalalhossain |
| 🎨 **Behance** | behance.net/shajalalhossain |

---

## 📄 License

```
MIT License

Copyright (c) 2025 Shajalal Hossain

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software to use, copy, modify, merge, or distribute —
provided that proper credit is given to the original author.
```

---

<div align="center">

**Shajalal Hossain** — Web Developer, Rangpur, Bangladesh

⭐ If you find this project helpful, please consider giving it a star!

[![GitHub stars](https://img.shields.io/github/stars/shajalalhossain/portfolio?style=social)](https://github.com/shajalalhossain/portfolio)

</div>
