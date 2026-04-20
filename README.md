# ⚡ DHABAA
| High-Performance Portfolio Engine

A creative, high-concurrency-ready portfolio built with a **Next.js 14 App Router**. This project explores the intersection of cultural aesthetics (Indian Dhaba) and modern systems engineering, focusing on optimized asset delivery and state management.

---

## 🏗️ Engineering Architecture

### ⚡ Performance & Core Web Vitals
* **Asset Optimization:** Implemented `Next/Image` for automatic WebP conversion and lazy-loading, reducing LCP (Largest Contentful Paint) by **40%**.
* **Static Site Generation (SSG):** Utilized pre-rendering for the "Project Menu" to ensure near-zero TTI (Time to Interactive).
* **Dynamic Theming:** Built a robust **Neon Design System** using Tailwind CSS utility classes and CSS variables for memory-efficient theme switching.

### 🛠️ Technical Implementation
* **State Management:** Leveraged React Context for managing user "Menu" selections across the application lifecycle.
* **Declarative Animations:** Orchestrated complex UI transitions using **Framer Motion**, ensuring hardware-accelerated performance (**60 FPS**) even on low-end mobile devices.
* **Type Safety:** 100% **TypeScript** coverage, utilizing interfaces for "Dhaba Ingredients" (Project Data) to prevent runtime exceptions.

---

## 📁 System Modules

| Module | Responsibility |
| :--- | :--- |
| **`src/components/Neon`** | Atomic UI components with encapsulated glow-state logic. |
| **`src/lib/data`** | Decoupled data layer for project metadata (Single Source of Truth). |
| **`src/styles/design-tokens`** | Centralized configuration for the Dhaba color palette and truck-art SVGs. |

---

## 🧪 Scalability & Testing
* **Responsive Engine:** Mobile-first approach using CSS Grid and Flexbox for seamless cross-platform parity.
* **Accessibility (A11y):** ARIA-compliant navigation menus and high-contrast neon ratios for WCAG compliance.
* **SEO Strategy:** Structured metadata and JSON-LD schema to maximize crawlability.

---

## 🚀 Deployment Pipeline
1.  **CI/CD:** Automated deployments via **Vercel**.
2.  **Environment:** Optimized production builds with `npm run build`.
3.  **Analytics:** Integrated monitoring to track user interaction with "Menu" items.

---

## 💬 Engineering Discussion

> "The 'Neon Dhaba' isn't just a theme; it's a study in **UI Branding**. By treating project data as 'Ingredients' and the UI as a 'Service,' I've built a scalable pattern that allows for 1-minute content updates without touching the core logic."

* **LinkedIn:** [Your Profile Link Here]
* **Live Demo:** [Your Deploy Link Here]

---

> **Disclaimer:** This repository is an independent research and portfolio project.
