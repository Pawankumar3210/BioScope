<div align="center">

# 🧬 BioScope

### AI-Powered Disease Intelligence & Healthcare Analytics Platform


<br />

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_Site-00d4ff?style=for-the-badge&logo=vercel&logoColor=white)][live-demo]
[![License: MIT](https://img.shields.io/badge/License-MIT-00ff88?style=for-the-badge)](#license)

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=for-the-badge)
![Vercel](https://img.shields.io/badge/Hosted_on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

<br />

⚡ **8 pages** &nbsp;•&nbsp; 📊 **Animated charts** &nbsp;•&nbsp; 🌗 **Dark & cream themes** &nbsp;•&nbsp; 🧠 **Simulated AI prediction** &nbsp;•&nbsp; 🗺️ **Interactive heatmap**

<br />

[**Live Demo**][live-demo] &nbsp;·&nbsp; [**Features**](#features) &nbsp;·&nbsp; [**Getting Started**](#getting-started) &nbsp;·&nbsp; [**Roadmap**](#roadmap)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Pages](#pages)
- [Real vs. Simulated](#real-vs-simulated)
- [Tech Stack](#tech-stack)
- [Design System](#design-system)
- [Project Structure](#project-structure)
- [How It Works](#how-it-works)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Troubleshooting](#troubleshooting)
- [Roadmap](#roadmap)
- [Disclaimer](#disclaimer)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

---

## Overview

**BioScope** is a front-end showcase of what a next-generation disease-intelligence platform could look like. It pairs a premium glassmorphism interface with animated analytics, an interactive outbreak heatmap and a simulated AI engine — the kind of command-center experience a public-health team might use to monitor outbreaks, explore trends and assess risk.

It is a **pure front-end project**: no backend, no database and no API keys. Every number comes from static mock data, which makes it easy to run, easy to customize and safe to deploy anywhere.

> [!WARNING]
> **Demo project — not a medical tool.** All data in BioScope is fictional and all "AI" outputs are simulated. It must not be used for diagnosis, treatment or public-health decisions. See the [Disclaimer](#disclaimer).

---

## Features

### Design & Experience

- **Glassmorphism UI** — translucent, blurred surfaces with soft neon glow in cyan, violet and green
- **Dark & cream-light themes** — one-click toggle in the top bar (deep-space black or warm parchment cream)
- **Particle network background** — a lightweight custom HTML5 Canvas animation with glowing, connected particles (no extra library)
- **Motion everywhere** — staggered entrance animations, hover lift and glow, scroll-reveal sections and an animated sidebar indicator, all powered by Framer Motion
- **Micro-interactions** — animated counters, progress bars, pulsing hotspots and a risk-percentage ring
- **Floating stat cards** on the landing-page hero

### Analytics Dashboard

- KPI cards with count-up animation (Active, Recovered, Critical, Deaths)
- Multi-disease trend **line chart** (2018–2024): COVID-19, Influenza, Dengue, Malaria and Tuberculosis
- Disease-burden **donut chart** with a color-coded legend
- Monthly cases vs. recoveries **bar chart**
- Regional severity breakdown with animated progress bars
- Glass-styled chart tooltips that match the theme
- **AI Insights** panel with generated-style observations and an export button

### AI-Style Tools (simulated)

- Health-metrics form: age, body temperature, symptoms, pre-existing conditions and region
- Multi-step "analyzing…" sequence followed by an AI result card
- Animated **risk ring** with Low / Medium / High classification and a recommended action
- Research cards with trend indicators, tags and AI-confidence bars

### Data & Mapping Tools

- Drag-and-drop **dataset upload** with animated drop-zone states and a preview table
- **Reports** library with Ready / Processing status badges and download buttons
- Interactive disease **heatmap** with pulsing hotspots, click-to-inspect region tooltips and region cards

### App Shell

- Fixed glass **sidebar** with eight routes and an "AI Engine Online" status widget
- **Top bar** with search field, voice-assistant button, notifications bell and user profile chip
- Client-side routing with React Router

---

## Pages

| Page | Route | What it does |
|---|---|---|
| **Home** | `/` | Landing page with animated hero, floating stat cards, feature grid, call-to-action and footer |
| **Dashboard** | `/dashboard` | KPI cards, disease-trend line chart, distribution donut, monthly bar chart and AI insights panel |
| **Statistics** | `/statistics` | Multi-year trends, monthly breakdown and a region-by-region severity table |
| **AI Prediction** | `/prediction` | Health-metrics form → simulated AI analysis → risk ring, predicted condition and recommendation |
| **Data Upload** | `/upload` | Drag-and-drop dataset zone with animated states and a preview table |
| **Reports** | `/reports` | Report library with status badges and download buttons |
| **Research Insights** | `/research` | AI-style research cards with trend indicators, tags and confidence bars |
| **Heatmaps** | `/heatmap` | Interactive disease-spread map with pulsing hotspots and region cards |

---

## Real vs. Simulated

BioScope is transparent about what is working and what is demo content.

**Legend:** ✅ Working &nbsp;·&nbsp; 🧪 Simulated with mock data &nbsp;·&nbsp; 🎨 UI only (not wired up yet)

| Feature | Status | Notes |
|---|:---:|---|
| Routing, layout, theme toggle, animations | ✅ | Fully functional |
| Charts (line, bar, donut) | ✅ | Rendered with Recharts from static mock data |
| Drag-and-drop / file picker | ✅ | Files are accepted, but their contents are not parsed |
| Dataset preview table | 🧪 | Shows sample rows |
| AI disease prediction | 🧪 | Randomly generated result after a short delay |
| AI insights, research summaries, reports | 🧪 | Hand-written placeholder text and numbers |
| Live-looking metrics | 🧪 | Animated counters over static values |
| Export / download buttons | 🎨 | Not connected to a file generator yet |
| Voice assistant, search, notifications | 🎨 | Visual placeholders for future features |

---

## Tech Stack

| Category | Technology | Role in BioScope |
|---|---|---|
| Framework | [React](https://react.dev) | Component-based UI (JavaScript / JSX) |
| Build tool | [Vite](https://vite.dev) | Fast dev server and production bundler |
| Styling | [Tailwind CSS v3](https://tailwindcss.com) | Utility classes plus custom glassmorphism styles |
| Animation | [Framer Motion](https://motion.dev) | Entrance, hover, scroll and layout animations |
| Charts | [Recharts](https://recharts.org) | Line, bar and pie/donut charts |
| Icons | [Lucide React](https://lucide.dev) | Crisp, consistent icon set |
| Routing | [React Router](https://reactrouter.com) | Client-side navigation between the 8 pages |
| Background | HTML5 Canvas | Custom particle network (zero dependencies) |
| State | React Context | Global dark / light theme |
| Hosting | [Vercel](https://vercel.com) | Zero-config deployment and CI/CD |

---

## Design System

### Color palette

| Token | Hex | Used for |
|---|---|---|
| Neon Cyan | `#00d4ff` | Primary accent, active states, links |
| Neon Violet | `#a855f7` | AI and prediction accents, gradients |
| Neon Green | `#00ff88` | Positive trends, recovery, "online" status |
| Signal Orange | `#ff6b35` | Warnings and rising trends |
| Alert Magenta | `#ff0080` | Critical and high-risk indicators |
| Void | `#020408` | Dark theme background |
| Cream | `#f5f0e8` | Light theme background |
| Espresso | `#2d2a24` | Light theme text |

### The glassmorphism recipe

Almost every card in BioScope is built from the same four lines:

```css
background: rgba(255, 255, 255, 0.03);
backdrop-filter: blur(20px);
border: 1px solid rgba(255, 255, 255, 0.08);
box-shadow: 0 8px 32px rgba(0, 0, 0, 0.4);
```

Hover states add a small upward lift (`y: -4`) and a colored glow using Framer Motion.

---

## Project Structure

```text
bioscope/
├── public/                      # Static files served as-is
├── src/
│   ├── assets/                  # Images and SVGs
│   ├── components/
│   │   ├── charts/              # Recharts wrappers
│   │   │   ├── DiseaseDonut.jsx
│   │   │   ├── MonthlyBar.jsx
│   │   │   └── TrendChart.jsx
│   │   ├── layout/              # App shell
│   │   │   ├── Layout.jsx       # Sidebar + top bar + particles + page wrapper
│   │   │   ├── Navbar.jsx       # Search, voice button, theme toggle, profile
│   │   │   └── Sidebar.jsx      # Left navigation with animated indicator
│   │   └── ui/                  # Reusable building blocks
│   │       ├── GlassCard.jsx    # Glass card with hover lift
│   │       ├── ParticlesBg.jsx  # Canvas particle background
│   │       └── StatCard.jsx     # KPI card with animated counter
│   ├── context/
│   │   └── ThemeContext.jsx     # Dark / light theme state
│   ├── data/
│   │   └── mockData.js          # All static demo data
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Dashboard.jsx
│   │   ├── Statistics.jsx
│   │   ├── Prediction.jsx
│   │   ├── Upload.jsx
│   │   ├── Reports.jsx
│   │   ├── Research.jsx
│   │   └── Heatmap.jsx
│   ├── App.jsx                  # Route definitions
│   ├── index.css                # Tailwind directives + global styles
│   └── main.jsx                 # React entry point
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
└── vite.config.js
```

---

## How It Works

```text
main.jsx
 └── App.jsx
      ├── ThemeProvider            ← dark / light state (React Context)
      └── BrowserRouter            ← client-side routing
           ├── /            → Home          (standalone landing page)
           ├── /dashboard   → Dashboard  ┐
           ├── /statistics  → Statistics │
           ├── /prediction  → Prediction │  Each of these pages is wrapped in <Layout>,
           ├── /upload      → Upload     │  which provides the Sidebar, the top Navbar
           ├── /reports     → Reports    │  and the particle background.
           ├── /research    → Research   │
           └── /heatmap     → Heatmap    ┘
```

- **Theme** — `ThemeContext` exposes `isDark` and `toggleTheme`. Any component reads them with the `useTheme()` hook.
- **Data** — charts, cards and tables import their data from `src/data/mockData.js`.
- **Animations** — Framer Motion's `motion` components handle entrances (`initial` / `animate`), hover effects (`whileHover`), scroll reveals (`whileInView`) and the shared sidebar indicator (`layoutId`).
- **Particles** — `ParticlesBg` draws on a full-screen `<canvas>` with `requestAnimationFrame` and cleans up after itself when the page unmounts.

---

## Getting Started

### Prerequisites

| Tool | Version | Check with |
|---|---|---|
| [Node.js](https://nodejs.org) | 20.19+ or 22.12+ (latest LTS recommended) | `node -v` |
| npm | Included with Node.js | `npm -v` |
| [Git](https://git-scm.com) | Any recent version | `git --version` |

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Pawankumar3210/bioscope.git

# 2. Move into the project folder
cd bioscope

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
```

Open **http://localhost:5173** in your browser — you should see the BioScope landing page. 🎉

> **Tip:** BioScope is desktop-first and looks best at 1280 px width or wider on a current version of Chrome, Edge, Safari or Firefox (the glass effect relies on `backdrop-filter`).

### Production build

```bash
npm run build      # creates an optimized build in /dist
npm run preview    # serves that build locally for a final check
```

---

## Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the dev server with hot reload at `http://localhost:5173` |
| `npm run build` | Create an optimized production build in `dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Check the code with ESLint |

---

## Customization Guide

### 1. Change the data

All demo data lives in one file: [`src/data/mockData.js`](src/data/mockData.js). Edit the arrays and every chart, card and table updates automatically.

| Export | Used by |
|---|---|
| `diseaseTrendData` | Trend line chart |
| `diseaseDistribution` | Donut chart and legend |
| `monthlyCases` | Monthly bar chart |
| `statsData` | Dashboard KPI cards |
| `regionData` | Heatmap and regional breakdown |
| `researchInsights` | Research Insights page |
| `riskFactors` | Prediction form dropdown |
| `reportsData` | Reports page |

> Adding a brand-new disease to the trend chart? Also add a matching `<Line dataKey="YourDisease" />` in `src/components/charts/TrendChart.jsx`.

### 2. Add a new page

**Step 1** — create `src/pages/MyPage.jsx`:

```jsx
import Layout from "../components/layout/Layout";

export default function MyPage() {
  return (
    <Layout title="My Page">
      <h1 className="text-white text-2xl font-bold">Hello BioScope 👋</h1>
    </Layout>
  );
}
```

**Step 2** — register the route in `src/App.jsx`:

```jsx
import MyPage from "./pages/MyPage";

// inside <Routes>
<Route path="/my-page" element={<MyPage />} />
```

**Step 3** — add it to the sidebar in `src/components/layout/Sidebar.jsx`:

```jsx
import { Star } from "lucide-react";

// inside the navItems array
{ path: "/my-page", label: "My Page", icon: Star },
```

### 3. Tune the particle background

Open `src/components/ui/ParticlesBg.jsx` and adjust two numbers:

```jsx
const particles = Array.from({ length: 80 }, () => ({ /* ... */ }));  // how many particles
if (dist < 120) { /* ... */ }                                          // how far lines connect
```

Fewer particles = better performance on low-end devices.

### 4. Change the colors

Search the project for the hex codes in the [color palette](#color-palette) (for example `#00d4ff`) and replace them. The theme background colors live in `src/context/ThemeContext.jsx` and `src/components/layout/Layout.jsx`.

---

## Deployment

BioScope is a static single-page app, so it can be hosted anywhere that serves the `dist/` folder. The recommended host is **[Vercel](https://vercel.com)** (the free tier is plenty).

### Deploy with Vercel + GitHub

1. Push the project to a GitHub repository.
2. Go to [vercel.com/new](https://vercel.com/new) and import the repository.
3. Confirm the build settings (Vercel detects them automatically):

| Setting | Value |
|---|---|
| Framework Preset | Vite |
| Build Command | `npm run build` |
| Output Directory | `dist` |
| Install Command | `npm install` |

4. Click **Deploy**. Every future `git push` to `main` redeploys automatically.

### Make direct links work (fix 404 on refresh)

React Router handles navigation in the browser, so create a `vercel.json` file in the project root. Without it, refreshing a page such as `/dashboard` returns a 404.

```json
{
  "rewrites": [{ "source": "/(.*)", "destination": "/index.html" }]
}
```

### Deploy with the Vercel CLI (alternative)

```bash
npm install -g vercel
vercel login
vercel --prod
```

---

## Troubleshooting

<details>
<summary><b>Build works on my PC but fails on Vercel with "Could not resolve './context/ThemeContext'"</b></summary>

<br />

Windows and macOS ignore letter case in file names, but Linux (which Vercel uses) does not — `ThemeContext.jsx` and `themecontext.jsx` are different files there. Check how Git actually stores your file names:

```bash
git config core.ignorecase false
git ls-files src/
```

If a name has the wrong casing, rename it in two steps (Git ignores a one-step, case-only rename), then push:

```bash
git mv src/context/themecontext.jsx src/context/temp.jsx
git mv src/context/temp.jsx src/context/ThemeContext.jsx
git commit -m "fix: filename casing"
git push
```

</details>

<details>
<summary><b>"It looks like you're trying to use tailwindcss directly as a PostCSS plugin"</b></summary>

<br />

BioScope uses **Tailwind CSS v3** (`@tailwind base;` directives plus `tailwind.config.js`). Tailwind v4 changed its PostCSS plugin, so install v3:

```bash
npm install -D tailwindcss@3 postcss autoprefixer
```

Then make sure `postcss.config.js` contains:

```js
export default {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
};
```

</details>

<details>
<summary><b>The page is completely blank or black</b></summary>

<br />

Press **F12** in your browser and open the **Console** tab — the first red error tells you which file and line is failing. A common one is *"Invalid hook call"*, which means a hook such as `useTheme()` was called outside a component function. Hooks must be called inside the component body.

</details>

<details>
<summary><b>Refreshing a page like /dashboard shows a 404 on Vercel</b></summary>

<br />

Add the `vercel.json` rewrite shown in [Deployment](#deployment), commit it and push.

</details>

<details>
<summary><b>Animations feel laggy</b></summary>

<br />

The glass blur and the particle network are the heaviest effects. Lower the particle count in `ParticlesBg.jsx` (see [Customization Guide](#customization-guide)) or reduce the `blur()` value on large cards.

</details>

---

## Roadmap

- [ ] Parse uploaded CSV files in the browser (e.g. PapaParse) and chart them instantly
- [ ] Connect real public-health data sources (WHO / CDC open-data APIs)
- [ ] Real PDF export for the dashboard and reports (jsPDF / html2canvas)
- [ ] True geographic map with Leaflet or MapLibre and choropleth layers
- [ ] Interactive 3D globe with React Three Fiber
- [ ] Voice assistant using the Web Speech API
- [ ] Working global search and filters
- [ ] Light theme for every card, chart and the landing page
- [ ] Route-transition animations with AnimatePresence
- [ ] Mobile and tablet layout with a collapsible sidebar
- [ ] Backend service and a trained model for genuine predictions
- [ ] TypeScript migration, unit tests (Vitest) and CI checks

Have an idea? [Open an issue](https://github.com/Pawankumar3210/bioscope/issues) — suggestions are welcome.

---

## Disclaimer

BioScope is an educational and design showcase.

- All statistics, reports, research summaries and predictions are **fictional placeholders**. They do not represent real epidemiological data.
- The "AI" prediction feature produces **randomly generated demo output** — no machine-learning model is running.
- Nothing in this project is medical advice, diagnosis or treatment. If you have health concerns, please consult a qualified healthcare professional.
- Organization, vaccine and disease names that appear in the sample text (for example WHO) are used only for illustrative realism and imply no affiliation or endorsement.

---

## Contributing

Contributions, ideas and bug reports are welcome!

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-idea`
3. Commit your changes: `git commit -m "feat: add amazing idea"`
4. Push the branch: `git push origin feature/amazing-idea`
5. Open a Pull Request

---

## License

Distributed under the **MIT License**. See the `LICENSE` file for details.

---

## Author

Built with ☕ and a lot of neon glow by **[@Pawankumar3210](https://github.com/Pawankumar3210)**.

If BioScope helped or inspired you, please consider giving the repository a ⭐ — it really helps!

---

## Acknowledgements

- [React](https://react.dev) — UI library
- [Vite](https://vite.dev) — build tooling
- [Tailwind CSS](https://tailwindcss.com) — styling
- [Motion (Framer Motion)](https://motion.dev) — animation
- [Recharts](https://recharts.org) — charts
- [Lucide](https://lucide.dev) — icons
- [React Router](https://reactrouter.com) — routing
- [Vercel](https://vercel.com) — hosting
- [Shields.io](https://shields.io) — README badges

<!-- 👇 Replace YOUR-PROJECT-NAME with your real Vercel project name. This is the ONLY place you need to change it. -->
[live-demo]: https://YOUR-PROJECT-NAME.vercel.app
