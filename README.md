# 🌍 Movade — Luxury Travel Agency & Experience Platform

[![Live Demo](https://img.shields.io/badge/Demo-Live%20on%20Vercel-success?style=for-the-badge&logo=vercel)](https://travel-agency-six-ruddy.vercel.app)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-blue?style=for-the-badge&logo=github)](https://github.com/Nikshithnayak/travel-agency)
[![Next.js](https://img.shields.io/badge/Next.js-14.2.35-black?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-v3.4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Three.js](https://img.shields.io/badge/Three.js-r160-white?style=for-the-badge&logo=threedotjs&logoColor=black)](https://threejs.org/)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-12.4-ff69b4?style=for-the-badge&logo=framer)](https://www.framer.com/motion/)

An immersive, state-of-the-art web platform engineered for luxury travel exploration. Featuring fluid canvas-based scroll animations, 3D interactive graphics, parallax galleries, and curated destination showcases.

---

## 🌐 Live Demo & Deployment

Experience the live application:  
👉 **[https://travel-agency-six-ruddy.vercel.app](https://travel-agency-six-ruddy.vercel.app)**

Mirror Deployment URL:  
👉 [https://travel-agency-ayuk9e343-nikshithnayaks-projects.vercel.app](https://travel-agency-ayuk9e343-nikshithnayaks-projects.vercel.app)

---

## ✨ Features & Highlights

- **🎞️ Canvas Frame-by-Frame Scroll Cinema**: Smooth scrubbed canvas sequence in the hero section dynamically tied to user scroll velocity.
- **🧭 Interactive Destination Discovery**: Deep dive into premier global destinations with categorized filters, pricing, and high-resolution imagery.
- **🚗 Let's Drive Road Trip Showcase**: Curated itineraries and premium vehicle options designed for road journey enthusiasts.
- **🌌 Constellation Testimonials**: Dynamic traveler reviews presented with celestial-inspired design and smooth interactivity.
- **🌐 3D Interactive Travel Network**: Real-time interactive globe and connection map powered by Three.js and `@react-three/fiber`.
- **🏎️ Lenis Smooth Scrolling**: Inertia-based momentum scrolling providing a buttery smooth browsing feel.
- **🔍 Multi-Param Search Widget**: Interactive booking/inquiry search widget with date pickers, destination queries, and passenger selectors.
- **📱 Fully Responsive & Glassmorphism Design**: Sleek typography, subtle blur overlays, and bespoke mobile-first responsive layouts.

---

## 🛠️ Technology Stack

| Layer | Technology | Purpose |
|---|---|---|
| **Framework** | Next.js 14 (App Router) | Server-side rendering, routing, static optimization |
| **UI Library** | React 18 | Component architecture and state management |
| **Styling** | Tailwind CSS | Modern utility-first responsive styling |
| **3D & Canvas** | Three.js, `@react-three/fiber`, `@react-three/drei` | 3D graphics rendering and camera controls |
| **Animations** | GSAP, Framer Motion | Timeline sequencing and micro-interactions |
| **Smooth Scroll** | Lenis | Momentum scroll orchestration |
| **Icons & Assets** | Lucide React | Clean, scalable vector iconography |
| **Deployment** | Vercel | Global edge CDN, CI/CD pipeline |

---

## 📁 Project Architecture

```
travel-agency/
├── app/
│   ├── favicon.ico
│   ├── globals.css         # Global styling & custom utility classes
│   ├── layout.tsx          # Root layout & font definitions
│   └── page.tsx            # Main landing page assembling sections
├── components/
│   ├── 3d/                 # Three.js 3D models & canvas components
│   ├── ui/                 # Reusable UI primitives (buttons, modals)
│   ├── hero-scroll-canvas  # Scrubbable hero canvas frame animation
│   ├── hero.tsx            # Hero presentation & search trigger
│   ├── search-widget.tsx   # Interactive travel search bar
│   ├── explore-escape.tsx  # Featured escapes & curated cards
│   ├── popular-destinations# Top trending locations
│   ├── lets-drive.tsx      # Road trip & driving experience section
│   ├── adventures-gallery  # Curated adventure photo grid
│   ├── parallax-gallery    # Depth-scrolling parallax visual cards
│   ├── why-choose.tsx      # Key benefits & service highlights
│   ├── popular-spots.tsx   # Detailed spot directory
│   ├── constellation-testimonials # Interactive review network
│   ├── travel-network.tsx  # 3D global network visualization
│   └── footer.tsx          # Comprehensive luxury footer
├── public/                 # Video preloader, frame sequences, images
├── tailwind.config.ts      # Design tokens, color palette, custom keyframes
├── tsconfig.json           # Strict TypeScript configuration
└── package.json            # Scripts & project dependencies
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18.x or later
- npm, yarn, or pnpm

### 1. Clone the repository

```bash
git clone https://github.com/Nikshithnayak/travel-agency.git
cd travel-agency
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

### 4. Build for production

```bash
npm run build
npm start
```

---

## 🚢 Deployment

This project is configured for continuous zero-config deployment on [Vercel](https://vercel.com):

1. Import repository on [Vercel](https://vercel.com/new).
2. Framework preset will automatically detect `Next.js`.
3. Click **Deploy**.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
