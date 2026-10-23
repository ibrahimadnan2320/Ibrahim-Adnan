# Ibrahim Adnan | Official Engineering Portfolio & Web Platform

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live%20Demo-ibrahim--adnan.vercel.app-00f0ff?style=for-the-badge&logo=vercel&logoColor=black)](https://ibrahim-adnan.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge)](LICENSE)
[![PWA Ready](https://img.shields.io/badge/PWA-v4.0%20Offline%20Ready-a855f7?style=for-the-badge&logo=pwa&logoColor=white)](https://ibrahim-adnan.vercel.app/)
[![Lighthouse 100](https://img.shields.io/badge/Lighthouse-100%20Performance-00f0ff?style=for-the-badge&logo=googlechrome&logoColor=white)](https://ibrahim-adnan.vercel.app/)

**A high-performance, 3D WebGL-powered engineering portfolio built with pure modern web technologies, ultra-realistic frosted glassmorphism, hardware-adaptive performance scaling, and zero-overhead offline PWA architecture.**

[Explore Live Portfolio](https://ibrahim-adnan.vercel.app/) • [Report Bug](https://github.com/ibrahimadnan2320/Ibrahim-Adnan/issues) • [Request Feature](https://github.com/ibrahimadnan2320/Ibrahim-Adnan/issues)

</div>

---

## ⚡ Highlights & Architectural Innovations

- 🌐 **Interactive 3D WebGL Core**: Real-time rotating crystal wireframe icosahedron with an ambient starfield particle cloud powered by Three.js. Includes delta-time independent damping (60Hz / 120Hz / 144Hz display parity) and modular time tracking to eliminate IEEE-754 precision drift.
- 🎴 **3D Perspective Coverflow Showcase with Hover Spec Drawer**: Hardware-accelerated 3D carousel with fluid fanning angles, touch swipe, keyboard navigation, signature neon edge halos, and interactive frosted-glass spec drawers that slide up smoothly on hover to reveal deliverables, tech stacks, and case study metrics.
- 🔬 **Instant Live Arsenal Search & Dynamic Counters**: Real-time client-side search input with live reactive category counters, filtering 36+ skills and competencies across Languages, Web & Full-Stack, SQA & Testing, and AI/Tools with zero latency.
- 💬 **Interactive WhatsApp Inquiry Presets**: One-click recruiter and client message templates pre-filling tailored inquiry briefs directly into WhatsApp.
- 🔲 **Cyber Architectural Grid & Space Grotesk Display**: Precision 36px x 36px background grid pattern paired with futuristic `Space Grotesk` display typography for high-impact headlines and numbered cyber telemetry badges.
- 🪟 **Ultra-Realistic Frosted Glassmorphism**: Multi-layered glass styling featuring `linear-gradient` face highlights, 1px specular top rims (`inset 0 1px 1px 0 rgba(255, 255, 255, 0.32)`), deep Gaussian blur (`24px`), and color saturation boost (`saturate(190%)`) that refracts colorful ambient glow orbs directly through the cards.
- 🛡️ **Hardware-Adaptive Performance Engine**: Dynamic detection for low-spec CPUs (`hardwareConcurrency <= 2`), constrained memory (`deviceMemory <= 3`), cellular throttling (`2g`/`slow-2g`), and battery conservation (`battery.level <= 20%`). Bypasses expensive multi-pass Gaussian blurs automatically to lock 60 FPS on any device.
- 📱 **Progressive Web App (PWA v7)**: Fully installable desktop and mobile app with Service Worker v7, `stale-while-revalidate` caching, offline navigation fallback, and automatic FIFO cache eviction capped at 50 items to protect mobile flash storage.
- 🔍 **SEO & Search Architecture**: Complete Schema.org JSON-LD `@graph` (`Person`, `WebSite`, `ProfilePage`, `SoftwareApplication`, `BreadcrumbList`), OpenGraph metadata, Twitter Cards, international `hreflang` alternates, and XML sitemaps with Google Image extensions (`xmlns:image`).
- ♿ **WCAG 2.1 AAA Accessibility**: Bypass skip-links, ARIA landmarks, carousel live regions, roving tabindex, modal keyboard focus traps with `Tab`/`Shift+Tab` cycling, `Escape` key dismissal, high-contrast mode overrides (`forced-colors: active`), and `prefers-reduced-motion` compliance.

---

## 🛠️ Tech Stack & Dependencies

| Layer | Technologies |
|---|---|
| **Core Runtime** | HTML5, Modern ECMAScript (ES2023+), Web APIs |
| **Styling & Design** | Tailwind CSS Engine, Cyber Grid Texture, Custom Glassmorphism Engine, CSS Containment Level 2 |
| **3D & Graphics** | Three.js (WebGL Renderer, BufferGeometry, PointsMaterial, PerspectiveCamera) |
| **Icons & Typography** | Space Grotesk, JetBrains Mono, Plus Jakarta Sans, FontAwesome 6.5.1 |
| **Offline & PWA** | Web App Manifest, Service Worker API (CacheStorage, Clients Claim, Skip Waiting) |
| **Deployment & Edge** | Vercel Serverless CDN, HTTP/2, HSTS Preload, Immutable Asset Caching |

---

## 📂 Project Structure

```text
├── index.html                                 # Single-page application entry point & styles
├── sw.js                                      # Service Worker (v4 cache & offline engine)
├── manifest.json                              # PWA installation manifest & shortcuts
├── vercel.json                                # Edge caching headers & security policies
├── sitemap.xml                                # Google XML sitemap with Image extensions
├── robots.txt                                 # Crawler rules & sitemap pointer
├── profile.png                                # High-res developer profile image
├── mak-and-sons.png                           # Production mockup: MAK & Sons Construction
├── iqra-academy.png                           # Production mockup: IQRA Quran Academy
└── *.pdf / *.jpg                              # Verified credentials & internship certificates
```

---

## 🚀 Getting Started

### Prerequisites
A modern web browser with WebGL support (Chrome, Firefox, Edge, Safari). No build tools, Node modules, or package managers required — zero dependencies!

### Local Development
1. **Clone the repository:**
   ```bash
   git clone https://github.com/ibrahimadnan2320/Ibrahim-Adnan.git
   cd Ibrahim-Adnan
   ```

2. **Serve locally:**
   You can use any local static server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Or using Node.js npx
   npx serve .
   ```

3. **Open in browser:**
   Navigate to `http://localhost:8000` to explore the portfolio.

---

## 💼 Featured Production Projects

### 1. [MAK & Sons Construction Website](https://mak-and-sons-construction.vercel.app/)
- **Category**: Corporate Architecture & Construction Platform
- **Features**: Interactive project galleries, architectural timelines, responsive design, and modern client inquiry interfaces.
- **Source**: [GitHub Repository](https://github.com/ibrahimadnan2320/mak-and-sons-website)

### 2. [IQRA Online Quran Academy](https://iqra-online-quran-academy.vercel.app/)
- **Category**: EdTech & Online Learning Platform
- **Features**: Multi-regional student onboarding, localized course curricula, responsive layouts, and interactive course selection.
- **Source**: [GitHub Repository](https://github.com/ibrahimadnan2320/IQRA-Online-Quran-Academy)

---

## 👤 Author

**Ibrahim Adnan**  
*Full-Stack Software Engineer & Software Quality Assurance Specialist*  
University of Management and Technology (UMT), Lahore, Pakistan

- 🌐 **Portfolio**: [ibrahim-adnan.vercel.app](https://ibrahim-adnan.vercel.app/)
- 💼 **LinkedIn**: [linkedin.com/in/ibrahim-adnan-a945263a2](https://linkedin.com/in/ibrahim-adnan-a945263a2)
- 🐙 **GitHub**: [@ibrahimadnan2320](https://github.com/ibrahimadnan2320)
- 📧 **Email**: [ibrahimadnan2320@gmail.com](mailto:ibrahimadnan2320@gmail.com)
- 💬 **WhatsApp**: [+92-3218470572](https://wa.me/923218470572)

---

## 📄 License

This project is licensed under the MIT License - feel free to use it for inspiration!
