# AI Chronicles

> An interactive timeline of 25 AI pioneers across 3,000 years — from mythic automata to generative AI.

![AI Chronicles](https://img.shields.io/badge/AI-Chronicles-B8965A?style=for-the-badge)
![Pure Vanilla](https://img.shields.io/badge/HTML%2FCSS%2FJS-Zero%20Dependencies-green?style=for-the-badge)
![Built by](https://img.shields.io/badge/Built%20by-Dhiraj-blue?style=for-the-badge)

---

##  Overview

**AI Chronicles** is a beautifully crafted, interactive scroll-driven timeline that tells the human story behind artificial intelligence. It features **25 pioneers** spanning **three millennia** — from Yan Shi's mechanical men in 1000 BC to Cristobal Valenzuela's Runway video generation today.

No frameworks. No build tools. No dependencies. Just pure HTML, CSS, and JavaScript — proving that elegant design doesn't need complexity.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **📜 6 Historical Eras** | Ancient → Mechanical → Mathematical → Birth of AI → Deep Learning → Generative |
| **🖼️ 25 Pioneer Portraits** | Circular framed images with hover effects and Wikipedia links |
| **🎨 Editorial Design** | Cormorant Garamond serif + Inter sans-serif + IBM Plex Mono for a timeless aesthetic |
| **📍 Interactive Scroll Rail** | Draggable progress thumb with era markers and hover tooltips |
| **📱 Fully Responsive** | Adapts from desktop grid to mobile single-column layout |
| **⚡ Zero Dependencies** | Pure vanilla HTML/CSS/JS — no React, no Vue, no npm install |
| **🔗 Playables SDK** | Integrated Meta Playables SDK for cross-platform compatibility |
| **🎯 Sticky Navigation** | Era headers stick as you scroll for context awareness |

---

## 🏛️ The 6 Eras & 25 Pioneers

### Ancient (c.1000 BC – 70 AD)
| Pioneer | Contribution | Legacy |
|---------|-------------|--------|
| Yan Shi | Mechanical Men | First myth |
| Aristotle | Syllogism | Rulebook |
| Hero of Alexandria | Programmable Automata | Scripted behavior |

### Mechanical (c.780 – 1315)
| Pioneer | Contribution | Legacy |
|---------|-------------|--------|
| Al-Khwarizmi | Algorithm | Named algorithm |
| Ismail al-Jazari | Programmable Orchestra | Programmable band |
| Ramon Llull | Ars Magna | Mechanical reasoning |

### Mathematical (1646 – 1864)
| Pioneer | Contribution | Legacy |
|---------|-------------|--------|
| Gottfried Wilhelm Leibniz | Binary | Digital foundation |
| Ada Lovelace | First Algorithm | First coder |
| George Boole | Boolean Algebra | Circuit language |

### Birth of AI (1903 – 2008)
| Pioneer | Contribution | Legacy |
|---------|-------------|--------|
| Alan Turing | Turing Machine | Defined AI question |
| Claude Shannon | Information Theory | Measured information |
| John von Neumann | Stored Program | Modern computer |
| John McCarthy | Coined "AI" | Named field |
| Marvin Minsky | Perceptrons | Mind as machine |
| Joseph Weizenbaum | ELIZA | AI conscience |

### Deep Learning (1947 – 1976)
| Pioneer | Contribution | Legacy |
|---------|-------------|--------|
| Geoffrey Hinton | Backpropagation | Learned features |
| Yann LeCun | ConvNets | Computer vision |
| Yoshua Bengio | Deep Learning | Persistence |
| Fei-Fei Li | ImageNet | Vision revolution |

### Generative (1976 – Present)
| Pioneer | Contribution | Legacy |
|---------|-------------|--------|
| Ian Goodfellow | GANs | Generative AI |
| Demis Hassabis | AlphaGo | AI for science |
| Ilya Sutskever | GPT | LLMs |
| Sam Altman | ChatGPT | Mainstream AI |
| Robin Rombach | Stable Diffusion | Open images |
| Cristobal Valenzuela | Runway | AI video |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Structure** | Semantic HTML5 |
| **Styling** | CSS Grid, Custom Properties, `clamp()`, `backdrop-filter` |
| **Interactivity** | Vanilla JavaScript (ES5+), Pointer Events, Intersection detection |
| **Typography** | Cormorant Garamond, Inter, IBM Plex Mono (Google Fonts) |
| **SDK** | Meta Playables SDK v1.0.0 |
| **Build** | None — open `index.html` in any browser |

---

## 🚀 Getting Started

### Quick Start
```bash
# Clone the repository
git clone https://github.com/dhirajmalwade/ai-chronicles.git

# Navigate to the project
cd ai-chronicles

# Open in your default browser
# Windows
start index.html
# macOS
open index.html
# Linux
xdg-open index.html
```

That's it. No `npm install`. No `npm run build`. No Webpack. Just open and enjoy.

### Project Structure
```
ai-chronicles/
├── index.html              # Main application (single file)
├── Comic D.png             # Brand logo
└── assets/                 # Pioneer portraits
    ├── 01_Yan_Shi.png
    ├── 02_Aristotle.png
    ├── ...
    ├── 25_Cristobal_Valenzuela.png
    └── Dhiraj.png          # Curator portrait
```

---

## 🎨 Design System

### Color Palette
| Token | Value | Usage |
|-------|-------|-------|
| `--ink` | `#0B0B0B` | Primary text |
| `--paper` | `#FAF7F0` | Background |
| `--paper2` | `#F0EBE0` | Secondary surfaces |
| `--gold` | `#B8965A` | Accent, CTAs |
| `--gold2` | `#D4B877` | Gold hover state |
| `--line` | `#E0D9C9` | Borders, dividers |

### Typography Scale
| Element | Font | Size |
|---------|------|------|
| Hero Title | Cormorant Garamond 700 | `clamp(3rem, 8vw, 6rem)` |
| Section Headers | Cormorant Garamond 700 | `2.3rem` |
| Pioneer Names | Cormorant Garamond 700 | `1.9rem` |
| Body Text | Inter 400 | `1rem` |
| Metadata | IBM Plex Mono 400 | `0.78rem` |

---

## 🌐 Deployment

This project is a **static single-page site** — deploy anywhere that serves HTML:

| Platform | Method |
|----------|--------|
| **GitHub Pages** | Push to `main` branch, enable Pages |
| **Vercel** | Connect repo, auto-deploy |
| **Netlify** | Drag & drop or connect Git |
| **Local** | Open `index.html` directly |

### GitHub Pages (Recommended)
1. Go to **Settings → Pages**
2. Source: `main` branch → `/root`
3. Your site will be live at `https://dhirajmalwade.github.io/ai-chronicles/`

---

## 📖 Design Philosophy

> *"Elegance is elimination."* — Cristóbal Balenciaga

AI Chronicles embraces **radical simplicity**:
- **One file** — no component tree, no state management, no build step
- **Zero dependencies** — no `node_modules` black hole
- **Progressive enhancement** — works without JavaScript (content is in HTML)
- **Semantic markup** — accessible by default
- **CSS-first animations** — smooth scrolling, hover states, transitions

This project proves that a museum-quality, editorial-grade web experience can be built with the same tools that existed in 1999 — just used with intention.

---

##  Acknowledgments

- **25 AI Pioneers** — The visionaries whose names populate this timeline
- **Wikipedia** — Primary source for biographical data and links
- **Google Fonts** — Cormorant Garamond, Inter, IBM Plex Mono
- **Meta Playables SDK** — Cross-platform event bridge

---

## 📬 Connect

**Curated & Built by [Dhiraj](https://www.linkedin.com/in/dhiraj-malwade-6a8385399/)**

- LinkedIn: [@dhiraj-malwade](https://www.linkedin.com/in/dhiraj-malwade-6a8385399/)


---

## 📄 License

This project is open source. Feel free to explore, fork, and build upon it.

---

<div align="center">

**From mechanical men to thinking machines — 3,000 years of human imagination.**

*From mythic automata to generative video — 25 pioneers who taught machines to reason, see, and create.*

⭐ Star this repo if you found it inspiring

</div>
