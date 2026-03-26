# 🌊 Ocean Depths — Into the Abyss

> *An immersive, scroll-driven deep-sea storytelling experience.*

![Ocean Depths Banner](https://img.shields.io/badge/Theme-Ocean%20Depths-00ffe7?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMSAzSDNjLTEuMSAwLTIgLjktMiAydjE0YzAgMS4xLjkgMiAyIDJoMThjMS4xIDAgMi0uOSAyLTJWNWMwLTEuMS0uOS0yLTItMnoiLz48L3N2Zz4=)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📖 About

**Ocean Depths** is an interactive storytelling website built for the *Frontend Odyssey* challenge. It takes users on a vertical descent from the sunlit ocean surface down to the deepest point on Earth — the Hadal Zone at 11,000 metres — using scroll interactions, animations, and immersive UI elements.

The scroll itself is the metaphor: the deeper you scroll, the darker the visuals, the higher the pressure, and the more alien the creatures.

---

## 🎯 Live Demo

🔗 **[View Live Site](https://glittering-praline-d65529.netlify.app/)**

📂 **[GitHub Repository](https://github.com/Dev2k30abrd/ocean-depths)**

---

## 🗺️ Story Structure (6 Sections)

| # | Section | Depth | Description |
|---|---------|-------|-------------|
| 1 | **Surface / Hero** | 0m | Entry point with animated fish, sunbeams, and scroll invitation |
| 2 | **Sunlight Zone** | 0–200m | Rich marine life, stat cards, hover-reveal creature cards |
| 3 | **Twilight Zone** | 200–1,000m | Pressure gauge, bioluminescence toggle, daily migration facts |
| 4 | **Midnight Zone** | 1,000–4,000m | Animated anglerfish, absolute darkness, crushing pressure |
| 5 | **Abyssal Zone** | 4,000–6,000m | Sonar ping interaction, accordion deep-sea facts |
| 6 | **Hadal Zone** | 6,000m+ | Finale — the deepest trench, return-to-surface button |

---

## ✅ Requirements Checklist

### Mandatory Requirements

- [x] **Story Structure** — 6 cohesive narrative sections forming a complete descent
- [x] **Scroll-Based Interactions** — Parallax sunbeams, scroll-triggered depth ticker & progress bar, IntersectionObserver reveal animations
- [x] **Interactive Elements** — Hover creature cards, bioluminescence toggle, sonar ping button, accordion FAQ, clickable fish
- [x] **Animations** — Custom loading screen with rising bubbles, floating anglerfish with glowing lure, fish swimming across screen, bioluminescent particle canvas
- [x] **Responsive Design** — Fully adapted layouts for desktop, tablet, and mobile

### Bonus Features

- [x] **Accessibility** — Skip link, ARIA roles & labels, `aria-live` depth reader, full keyboard navigation on every interactive element
- [x] **Reduced Motion** — `prefers-reduced-motion` media query respected
- [x] **Performance** — RAF-throttled scroll listener, IntersectionObserver for lazy reveals, CSS-only animations where possible
- [x] **Custom Cursor** — Bioluminescent cursor with magnetic hover effect (desktop)
- [x] **Unique Interactions** — Real-time depth ticker counting to 11,000m, fish that pause mid-swim when clicked, sonar pulse reset on click

---

## 🛠️ Technologies Used

| Category | Technology |
|----------|-----------|
| Markup | HTML5 (semantic) |
| Styling | CSS3 (custom properties, keyframes, grid, flexbox) |
| Scripting | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Cinzel Decorative, Cormorant Garamond, Space Mono |
| Animations | Native CSS animations + `requestAnimationFrame` |
| Canvas | HTML5 Canvas API (bioluminescent particles) |
| Observers | IntersectionObserver API (scroll reveals) |

> No frameworks. No build tools. No dependencies. Pure HTML/CSS/JS — one single file.

---

## 🚀 Getting Started

### Run Locally

```bash
# Clone the repository
git clone https://github.com/Dev2k30abrd/ocean-depths.git

# Open in browser
cd ocean-depths
open index.html
```

Or simply double-click `index.html` to open it in your browser.

### Deploy

The project is a single `index.html` file — deploy anywhere:

- **Netlify** — Drag & drop the folder at [netlify.com](https://netlify.com)
- **Vercel** — Import GitHub repo at [vercel.com](https://vercel.com)
- **GitHub Pages** — Enable in repository Settings → Pages → main branch

---

## 📁 Project Structure

```
Ocean_Depth/
└── index.html       # Complete project — HTML + CSS + JS in one file
└── README.md        # This file
```

---

## 🎨 Design Decisions

- **Vertical scroll = depth descent** — The page architecture mirrors the ocean itself
- **Color palette shifts** — From bright cyan (#00c9e8) at the surface to near-black (#000308) at the hadal zone
- **Typography** — *Cinzel Decorative* for epic zone titles, *Cormorant Garamond* for narrative body text, *Space Mono* for scientific data readouts
- **Bioluminescent accent** — `#00ffe7` used as the signature glow color throughout, referencing real deep-sea bioluminescence
- **No frameworks** — Kept vanilla for maximum performance and a clean, submission-ready codebase

---

## ♿ Accessibility

- Semantic HTML5 landmarks (`<section>`, `<nav>`, `aria-label>`)
- Full keyboard navigation on all interactive elements
- `aria-live` region for the depth ticker (screen reader friendly)
- Skip-to-content link
- `prefers-reduced-motion` support — all animations disabled for users who prefer it
- Sufficient colour contrast on all text elements

---

## 📝 Project Description

*Ocean Depths* is an immersive, scroll-driven storytelling experience that takes users on a vertical descent from the sunlit ocean surface to the deepest point on Earth — the Hadal Zone at 11,000 metres.

The narrative is structured across six zones — Surface, Sunlight (0–200m), Twilight (200–1,000m), Midnight (1,000–4,000m), Abyssal (4,000–6,000m), and Hadal (6,000m+) — each revealing progressively darker visuals, crushing pressure statistics, and increasingly alien creatures. The scroll itself becomes the metaphor: the deeper you go, the more immersive and mysterious the experience becomes.

Key interactions include hover-reveal creature cards, a bioluminescence toggle that illuminates the twilight zone, a clickable sonar ping in the abyssal section, an expandable accordion FAQ, and fish that can be clicked mid-swim to pause them. A real-time depth ticker counts down to 11,000 metres as the user scrolls, reinforcing the narrative immersion.

Built entirely with vanilla HTML, CSS, and JavaScript — no frameworks — to maximise performance. Animations use CSS keyframes and `requestAnimationFrame` for smoothness. The site is fully responsive across mobile, tablet, and desktop, and meets WCAG accessibility standards with full keyboard navigation, ARIA labels, and `prefers-reduced-motion` support.

---

## 👩‍💻 Author

**Devansh Rai**
GitHub: [@Dev2k30abrd](https://github.com/Dev2k30abrd)

---

*Built for Frontend Odyssey — The Interactive Web Experience Challenge*
