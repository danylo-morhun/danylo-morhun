# Hi, I'm Danylo Morhun 👋

Senior Full-Stack Engineer with 4.5 years of production experience across React, Next.js, Vue 3, Nuxt 3, Node.js, and PostgreSQL in fintech and B2B SaaS. Experienced owning features end-to-end — from system architecture and state management to shipped, performant UIs, data-heavy dashboards, real-time feeds, and payment flows.

Portfolio: [danylomorhun.com](https://danylomorhun.com)  
Contact: [danymorhun@gmail.com](mailto:danymorhun@gmail.com) | Katowice, Poland  

---

## Featured Engineering Projects

### 1. [seikatsu](https://github.com/danylo-morhun/seikatsu) — Modular Ecosystem Super-App

> **Next.js 15 (App Router)** · **React 19** · **Turborepo** · **Drizzle ORM** · **Neon Postgres** · **Biome** · **NextAuth v5**

Production monorepo unifying multi-domain daily utilities under a single authenticated shell.

- **Kuroji**: Double-entry financial accounting ledger with multi-currency balance tracking & Privat24 import parsers.
- **Seiryu**: O(1) drag-and-drop Kanban board using fractional indexing to eliminate sequential DB updates.
- **Kyū & Keizoku**: Job application tracker with recruitment pipeline analytics + habit tracking engine.
- **Tsundoku**: Personal book reading tracker integrated with Open Library REST API.
- **Live Demo**: [seikatsu.danylomorhun.com](https://seikatsu.danylomorhun.com)

---

### 2. [zielarnia](https://github.com/danylo-morhun/zielarnia) — E-Commerce Platform

> **Next.js 16 (App Router)** · **Prisma ORM** · **Neon Postgres** · **Przelewy24** · **BaseLinker API** · **InPost**

Production e-commerce engine built for health supplements, bio-products, and vitamins.

- **Financial Integrity**: Cryptographic HMAC-SHA384 signature verification & constant-time comparison for payment webhooks.
- **Logistics Integration**: BaseLinker stock sync hub for Allegro, plus automated InPost Paczkomaty shipping label generation.
- **Regulatory Compliance**: GIS/Sanepid health claim schema & rich-text XSS sanitization.
- **DevOps Pipeline**: Ephemeral Neon Postgres branch provisioning per CI run for isolated E2E checkout testing.

---

### 3. [danylomorhun.com](https://github.com/danylo-morhun/danylomorhun.com) — Nuxt 4 SSR Portfolio & Visual Engine

> **Nuxt 4 (SSR)** · **Vue 3.5** · **TypeScript** · **Tailwind CSS** · **GSAP 3** · **Three.js** · **Nitro Engine**

Universal server-rendered portfolio engine built for maximum search engine indexing, zero layout shift, and visual performance.

- **Core Web Vitals**: 100/100 Lighthouse performance rating with TTFB < 100ms and zero cumulative layout shift (CLS = 0).
- **Dynamic Edge Previews**: Edge-rendered social share card generator utilizing Satori HTML-to-SVG compilation (`nuxt-og-image`).
- **Graphics & Motion Pipeline**: Hardware-accelerated GSAP 3 timeline animations and Three.js 3D WebGL viewport integration.
- **Architecture**: Nuxt 4 hybrid rendering powered by the Nitro engine, Nuxt i18n route localization, and dynamic dark mode.
- **Live Site**: [danylomorhun.com](https://danylomorhun.com)

---

## Technical Skills & Toolchain

| Category | Stacks & Technologies |
| :--- | :--- |
| **Frontend Frameworks** | React, Next.js (App Router), Vue 3 (Composition API), Nuxt 3, TypeScript, JavaScript (ES6+), Tailwind CSS, SCSS, Shadcn UI, Radix UI |
| **State & Validation** | Redux Toolkit, React Query / TanStack Query, Zustand, Pinia, Vuex, React Hook Form, Zod, RTK Query |
| **APIs & Real-Time** | REST, WebSockets, GraphQL, gRPC, Axios, ofetch |
| **Data Viz & Tables** | D3.js, AG Grid, Recharts, ApexCharts, Chart.js |
| **Auth & Security** | Auth0, NextAuth v5, JWT, XSS/CSRF mitigation |
| **Backend & DB** | Node.js, NestJS, Python (Django / DRF), PostgreSQL (Neon, Supabase), Drizzle ORM, Prisma ORM, Redis (Upstash) |
| **Testing Suite** | Playwright, Vitest, Jest, Cypress, React Testing Library (RTL), TDD, E2E |
| **Infra & Tooling** | AWS (S3, CloudFront), Docker, GitHub Actions, GitLab CI/CD, Turborepo, Biome, Vite, Webpack, Storybook, Git |

---

## Engineering Standards & Practices

- **Strict Type Safety & Schema Contracts**: End-to-end type safety enforced across client-server boundaries using TypeScript strict mode, ORM schema generators, and runtime Zod validation.
- **Automated Continuous Integration Gates**: Multi-stage parallel CI/CD workflows executing static typechecking, automated test suites (Vitest, Playwright), dependency security audits, and zero-warning lint checks before merge.
- **Performance & Core Web Vitals Optimization**: Strategic Server-Side Rendering (SSR), route-level code splitting, virtualized data tables, and image/font optimization to achieve Lighthouse 95+ performance ratings.
- **Security & Financial Integrity**: Defensive web engineering with cryptographic HMAC signature verification for payment webhooks, constant-time timing-safe string comparison, and rich-text XSS sanitization.
