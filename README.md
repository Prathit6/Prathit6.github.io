# Prathit6.github.io

> Personal portfolio of **Prathit Dode** — Full-Stack Developer & Software Engineering student.

[![Live](https://img.shields.io/badge/Live-prathitdode.me-22c55e?style=flat-square&logo=googlechrome&logoColor=white)](https://prathitdode.me)
[![GitHub](https://img.shields.io/badge/GitHub-Prathit6-181717?style=flat-square&logo=github)](https://github.com/Prathit6)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-prathit--d-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/prathit-d/)

---

> **Note:** This repository hosts the **production build** deployed via GitHub Pages.
> The source code (React + Vite) lives in a separate private repository.

---

## ✨ Features

- **Terminal-inspired dark UI** with monospace aesthetics and dashed-border layout
- **Cinematic page load** — blur-to-sharp staggered entrance on every section
- **Scroll reveal** — each section drifts in as you scroll via `IntersectionObserver`
- **GitHub Contributions Graph** — live activity heatmap
- **AI Chat Widget** — conversational assistant built into the portfolio
- **Projects showcase** — VANI.AI, Tvarit-JS, AiGallery, Prime-gen.cpp, Chatbot, and more
- **Experience & Education** timeline with expandable course details
- **Typewriter role animation** — cycles through Full-Stack, C++, React, Node.js roles
- **Resume download** linked directly from the hero section
- **Responsive design** — mobile, tablet, and desktop ready

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React 18, Vite |
| Styling | CSS-in-JS, CSS variables, keyframe animations |
| Routing | React Router v6 |
| Icons | Lucide React |
| Animations | `IntersectionObserver` scroll reveal, `cubic-bezier` transitions |
| Deployment | GitHub Pages (this repo) |
| Domain | Custom — `prathitdode.me` via `CNAME` |

---

## 📁 Repo Structure

```
Prathit6.github.io/
├── assets/              # Compiled JS, CSS, images
├── index.html           # Production entry point
├── profile-icon.png     # Profile photo
├── Resume_Prathit_Dode.pdf
├── vite.svg
└── CNAME                # Custom domain → prathitdode.me
```

---

## 🌐 How It's Deployed

The React source is built with Vite and the `dist/` output is pushed here directly. GitHub Pages serves `index.html` as the SPA entry point.

```bash
# From the source repo
npm run build
cp -r dist/* ../Prathit6.github.io/
cd ../Prathit6.github.io
git add .
git commit -m "deploy: update build"
git push origin main
```

GitHub Pages automatically serves the latest `main` branch at [prathitdode.me](https://prathitdode.me).

---

## 🚀 Projects Featured

| Project | Description | Stack |
|---|---|---|
| VANI.AI | AI-powered e-commerce platform | JavaScript |
| Tvarit-JS | High-speed JavaScript runtime toolkit | JavaScript |
| AiGallery | AI-generated image gallery & curator | JavaScript |
| Prime-gen.cpp | Sieve of Eratosthenes implementation | C++ |
| Linkdin-Share | One-click LinkedIn post automation | JavaScript |
| Chatbot | Conversational AI assistant | JavaScript |

---

## 📬 Contact

| | |
|---|---|
| Twitter/X | [@Prathitdode](https://x.com/Prathitdode) |
| LinkedIn | [prathit-d](https://www.linkedin.com/in/prathit-d/) |
| GitHub | [Prathit6](https://github.com/Prathit6) |

---

<div align="center">
  Built with ☕ and React &nbsp;·&nbsp; <a href="https://prathitdode.me">prathitdode.me</a>
</div>
