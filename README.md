# Rameshkumar K — Portfolio

Personal portfolio site built with **React, Vite and Tailwind CSS**. Single-page, fully responsive, with light/dark theming, scroll-spy navigation, and dynamic SEO meta tags.

🔗 **Live:** https://rameshkumark.vercel.app

---

## 🧱 Tech Stack

| Layer | Technology |
|---|---|
| Framework | React 18 |
| Build tool | Vite |
| Styling | Tailwind CSS, CSS custom properties |
| Icons | lucide-react |
| Fonts | Space Grotesk, Manrope, Satoshi |
| Hosting | Vercel |

> This is the stack of **this website**. For my engineering skills, see the [About](#-about-me) section below or the [live site](https://rameshkumark.vercel.app).

---

## ✨ Features

- **Light / dark theming** driven by CSS custom properties — no runtime theme library
- **Scroll-spy navigation** that highlights the active section
- **Dynamic SEO** — `title`, `description`, `keywords` and Open Graph tags set at runtime
- **Custom cursor** with hover states (desktop only, gracefully hidden on touch)
- **Single source of truth** — all content lives in one `RESUME_DATA` object
- **Responsive timeline** for the experience section
- **Fully responsive** with touch-optimised targets on mobile

---

## 📁 Project Structure

```
My-Portfolio/
├── src/
│   ├── App.jsx          # All sections + RESUME_DATA (single source of truth)
│   ├── main.jsx         # React entry point
│   └── index.css        # Tailwind directives
├── public/
├── index.html
├── tailwind.config.js
├── vite.config.js
└── package.json
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18 or later
- npm

### Installation

```bash
git clone https://github.com/rameshkumark24/My-Portfolio.git
cd My-Portfolio
npm install
```

### Run locally

```bash
npm run dev
```

Open http://localhost:5173

### Build for production

```bash
npm run build
npm run preview
```

---

## 🎨 Customisation

All content is in a single `RESUME_DATA` object at the top of `src/App.jsx`. Edit it and everything updates — no other file needs touching.

```js
const RESUME_DATA = {
  name: "...",
  role: "...",
  tagline: "...",
  skills:      [ /* skill cards */ ],
  projects:    [ /* project cards — supports `link`, `live`, `highlight` */ ],
  experience:  [ /* timeline entries */ ],
  achievements:[ /* ... */ ],
  certifications: [ /* ... */ ]
};
```

**Theming:** colours live as CSS variables under `.light-theme` and `.dark-theme` in the `<style>` block inside `App.jsx`.

---

## 🚢 Deployment

Deployed on Vercel with the default Vite preset:

- **Framework preset:** Vite
- **Build command:** `npm run build`
- **Output directory:** `dist`

---

## 👤 About Me

Computer Science Engineering (AI & ML) undergraduate at KPR Institute of Engineering and Technology, focused on **backend and full-stack software engineering**.

**Core stack:** Java · Spring Boot 3 · Spring Security · Spring Data JPA · Hibernate · Python · FastAPI · React · TypeScript · MySQL · PostgreSQL · Docker

**Selected work**
- **[Placement Management System](https://github.com/rameshkumark24/placement_system)** — full-stack Java platform: Spring Boot 3 backend, React frontend, JWT with access + refresh tokens, role-based authorization, Swagger-documented APIs, Docker Compose, deployed to production · [Live](https://placement-system-five.vercel.app)
- **[NexOps](https://github.com/rameshkumark24/abb-nexops)** — real-time Industrial IoT predictive maintenance platform (MQTT, WebSockets, ML anomaly detection) · **Top 6 of 1,600+ teams, ABB Accelerator 2026**
- **[DSAPath](https://github.com/rameshkumark24/dsapath)** — DSA preparation and progress-tracking platform · [Live](https://dsapathvictory.vercel.app)

**Also:** 200+ DSA problems solved in Java · Hushh Community Champion (open source) · Top 45 institutional teams, Smart India Hackathon 2025 · Finalist, Flinders University AI Competition · Public Relations Officer coordinating departmental technical events for 200+ participants

---

## 📬 Contact

[Portfolio](https://rameshkumark.vercel.app) · [LinkedIn](https://www.linkedin.com/in/rameshkumark24/) · [GitHub](https://github.com/rameshkumark24) · [LeetCode](https://leetcode.com/u/Ramesh_Kumar_K/) · rameshkumaroff@gmail.com

---

## 📄 License

MIT — feel free to fork and adapt. A link back is appreciated but not required.
