# 🎨 Amrutha Jalaja Devi Portfolio — Contemporary Fine-Art Website (UK Artist)

> A modern, high-performance web platform built for a UK-based contemporary figurative painter and public muralist, engineered with cutting-edge web technologies to deliver exceptional user experiences, lightning-fast load times, and top-tier search engine visibility.

[🔗 **View Live Website**](https://amrithajalajadevi.com)

---

## ✨ Project Overview

**Amrutha Jalaja Devi Portfolio** is a bespoke, enterprise-grade digital solution crafted specifically for a professional fine-art practice with an international exhibition record. Designed with a conversion-first mindset and a polished gallery aesthetic inspired by European art institutions, the platform bridges the gap between stunning visual design and robust technical architecture.

Because this repository serves as a showcase of our development capabilities, the codebase is kept private. However, the live application demonstrates our commitment to clean code, scalable architecture, and meticulous attention to detail — from the sub-second page loads to the pixel-accurate reproduction of high-resolution artwork.

**What the client needed, and what we delivered:**

- A gallery-grade presentation where paintings, murals, and limited-edition prints are shown at full fidelity — without slow page loads.
- Full editorial independence: the artist (or any team member) publishes, reorders, and re-crops content from an embedded CMS with zero deployments.
- A site that ranks, loads, and converts: semantic markup, automated metadata, and a spam-proof inquiry pipeline that routes real commissions to the artist's inbox.

---

## 🚀 Core Features & Capabilities

* **⚡ Blazing-Fast Performance:** Optimized asset delivery, React Server Components, static generation with incremental revalidation, and edge caching ensure near-instantaneous page transitions. Measured at **97/100 Lighthouse performance (desktop), 0 ms total blocking time, and 0.00 CLS**.
* **📱 Fully Responsive Design:** Meticulously styled layouts that scale seamlessly across mobile devices, tablets, and ultra-wide desktop monitors — including a dedicated mobile navigation drawer and touch-friendly artwork lightbox.
* **🔍 SEO-Optimized Architecture:** Built-in semantic HTML5 structure, automated metadata and Open Graph generation, plus a **dynamically generated XML sitemap** that inventories every published artwork, mural, and exhibition for maximum search engine reach.
* **🖼️ Intelligent Image Pipeline:** Editor crop rectangles and focal hotspots set in the CMS are translated into pixel-perfect CDN URLs, with Low-Quality Image Placeholders and blur-up decoding so the *correct* part of every painting is visible at every viewport size — with zero layout shift.
* **🗂️ Headless CMS with Embedded Studio:** A full Sanity Studio mounted at `/studio` lets the team manage artworks, exhibitions, public art, press, CV, and site settings in real time — with role-friendly singletons, GROQ-powered queries, and instant publishing.
* **📬 Secure Contact & Inquiry System:** Server-side form handling with strict Zod validation, honeypot anti-spam protection, and transactional email delivery via Resend — with reply-to routing straight to the artist and dynamic recipient configuration stored in the CMS.
* **♿ Accessible (A11y) Interface:** Semantic landmarks, proper ARIA labeling, keyboard-navigable galleries and modals, and high-contrast typography — audited at **100/100 for accessibility**.
* **🌓 Refined, Brand-Led Aesthetics:** A bespoke fine-art palette (deep burgundy, warm canvas neutrals), editorial serif headings, and smooth Framer Motion micro-interactions that feel premium without hurting load times.

---

## 🛠️ Tech Stack & Architecture

This project is built using a modern, scalable, and type-safe technology stack:

* **Frontend Framework:** **Next.js 16 (App Router)** with **React 19** — Server Components for optimized rendering and reduced client-side bundle sizes, Server Actions for mutations, and Incremental Static Regeneration for instant content updates.
* **Styling & UI:** **Tailwind CSS v4** for maintainable, utility-first styling, **Framer Motion** for fluid micro-interactions, and **TypeScript 5** for strict, compile-time-safe types across every query and component.
* **Content & Media:** **Sanity** headless CMS with **next-sanity** GROQ querying and `@sanity/image-url` crop/hotspot optimization served through a global image CDN.
* **Backend & API:** Next.js **Server Actions** (no legacy API routes) with **Zod** validation and **Resend** transactional email — secure data handling with rapid server-side execution.
* **Deployment & Hosting:** Deployed on **Vercel's globally distributed edge network** with automatic SSL, preview deployments per branch, and webhook-driven cache revalidation — minimal latency worldwide.

---

## 📊 Performance & Lighthouse Audits

We prioritize uncompromising web performance. The live application underwent rigorous auditing to achieve exceptional scores across all major Google Lighthouse benchmarks.

**Audited:** 16 October 2026 · **Lighthouse 13.5.0** · Run against the production URL ([amrithajalajadevi.com](https://amrithajalajadevi.com))

### Desktop

| Metric | Score | Status |
| --- | --- | --- |
| **Performance** | **97** | 🟢 Exceptional |
| **Accessibility** | **100** | 🟢 Fully Compliant |
| **Best Practices** | **100** | 🟢 Optimized |
| **SEO** | **100** | 🟢 Top Tier |

### Core Web Vitals (Lab Measurements)

| Metric | Desktop | Mobile (simulated 4G) | Target |
| --- | --- | --- | --- |
| **First Contentful Paint** | **0.61 s** | 1.8–2.0 s | < 1.8 s |
| **Largest Contentful Paint** | **1.20 s** | 4.7 s* | < 2.5 s |
| **Cumulative Layout Shift** | **0.00** | **0.00** | < 0.1 |
| **Total Blocking Time** | **0 ms** | 21–29 ms | < 200 ms |
| **Speed Index** | **1.15 s** | 2.7–3.5 s | < 3.4 s |
| **Transferred Payload** | 864 KiB | 767 KiB | — |

\* Lighthouse's mobile profile simulates a throttled 4G connection with a 4× CPU slowdown; the layout is perfectly stable (CLS 0.00) and essentially free of main-thread blocking (TBT < 30 ms) on both profiles. Mobile LCP is dominated by the intentionally full-bleed, high-resolution hero artwork.

**Why these numbers matter for your business:** every second of load time costs conversions and search rankings. Sub-second first paint, zero layout shift, and zero blocking time mean visitors see the work immediately, never fight a jumping page, and Google rewards the site with stronger organic visibility.

---

## 📸 Project Showcase & Screenshots

### 🖥️ Desktop View

> *Homepage desktop layout: editorial serif hero, fixed navigation rail, and full-bleed artwork presentation.*

![Desktop homepage — Amrutha Jalaja Devi portfolio](screenshots/desktop-home.png)

### 🖼️ Gallery & Work Index

> *Masonry project display with category filtering and responsive grid of paintings, murals, and prints.*

![Desktop work gallery — masonry grid with filters](screenshots/desktop-work.png)

### 📱 Mobile Experience

> *Mobile viewport at 2× device pixel ratio displaying responsive navigation and fluid typography.*

![Mobile homepage — responsive layout](screenshots/mobile-home.png)

### ⚙️ Admin Dashboard

> *[Insert Screenshot: Embedded Sanity Studio (`/studio`) managing artworks, exhibitions, and site settings]*

---

## 🌐 Explore the Live Application

Experience the speed, responsiveness, and design fidelity firsthand:

👉 **[Visit Live Website](https://amrithajalajadevi.com)** · 🎛️ **[Embedded Studio](https://amrithajalajadevi.com/studio)** *(access requires credentials)*

---

## 👨‍💻 About the Developer — Let's Build Yours

This project is a live example of the work we deliver for clients: **type-safe, CMS-driven, performance-obsessed web platforms** that are as pleasant for the client's team to manage as they are for their visitors to use.

**If you are a gallery, studio, brand, or independent professional and you need a website that:**

- loads in under a second and scores 100 in accessibility, best practices, and SEO,
- lets your team publish content without touching a developer,
- makes your work — and your business — look unmistakably premium,

**…let's talk.**

- 📧 Email: **abhinandps.pro@gmail.com**
- 🔗 LinkedIn: **https://www.linkedin.com/in/psabhinand/**
- 💼 Freelance profile: **https://short.do/Kz9ZJK**
- 🐙 GitHub: **https://github.com/Abhinandps**

*Available for new web design & development engagements.*

---

## 📄 License & Copyright

All design assets, proprietary source code, and custom implementations are protected.

*© 2026 Amrutha Jalaja Devi & Development Team. All rights reserved.*
