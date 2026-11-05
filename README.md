# Personal Developer Portfolio — Charan Goud Ediga

A responsive personal developer portfolio website built from scratch using pure, semantic **HTML5**, **CSS3**, and **vanilla JavaScript** (no UI libraries, frameworks, or CSS preprocessors).

This site showcases full-stack and backend software engineering projects, core technical competencies, professional credentials, and direct contact avenues.

---

## 📋 Features & Implementation

### 1. Semantic Architecture
- Built with HTML5 semantic landmark elements: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`.
- Structured with clear heading hierarchies (`h1` through `h3`) and accessible labeling (`aria-label`, `aria-expanded`, `role`).

### 2. Fully Responsive Layout
- Fluid layout designed and tested across:
  - **Mobile**: 375px+
  - **Tablet**: 768px
  - **Desktop**: 1280px+
- Uses CSS Grid, Flexbox, and CSS clamp typography to adapt smoothly without horizontal overflow.

### 3. JavaScript Interactions
- **Interactive Project Filtering**: Live filtering across project categories (Full-Stack/Backend, Web Client, and Advanced Web3/AI) with smooth CSS visibility transitions.
- **Theme Switcher**: Dark Mode and Light Mode toggle that stores the user preference in `localStorage`.
- **One-Click Email Copy**: Native Clipboard API interaction with an animated toast notification.
- **Accessible Mobile Navigation**: Hamburger drawer toggle with auto-close functionality on link navigation.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic structure, accessibility landmarks, and content hierarchy |
| **CSS3** | Custom variables, Flexbox, Grid, glassmorphism, responsive media queries |
| **JavaScript (ES6+)** | Category filter logic, theme switching, clipboard API, mobile drawer |

---

## 📁 Repository Structure

```text
├── index.html     # Main markup and semantic sections
├── style.css      # Custom styling, design tokens, and media queries
├── script.js      # Vanilla JS interactions and DOM manipulation
└── README.md      # Project overview and local execution guide
