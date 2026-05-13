# 🏍️ IronLink | Premium Moto-Performance Platform

> A high-performance, AR-integrated SaaS e-commerce ecosystem for motorcycle enthusiasts. Engineered with a "Neon-Dark" aesthetic and edge-computing architecture for lightning-fast parts procurement.

<p align="center">
  <a href="https://nextjs.org/" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=nextjs" alt="nextjs" width="70" height="70"/> </a>
<a href="https://bun.sh/" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=bun" alt="bun" width="70" height="70"/> </a>
  <a href="https://nodejs.org/en" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=nodejs" alt="nodejs" width="70" height="70"/> </a>
<a href="https://vitejs.dev/" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=vite" alt="vite" width="70" height="70"/> </a>
<a href="https://supabase.com/" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=supabase" alt="supabase" width="70" height="70"/> </a>
<a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=tailwind" alt="tailwind" width="70" height="70"/> </a>
<a href="https://cloudflare.com/" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=cloudflare" alt="cloudflare" width="70" height="70"/> </a>
</p>

## 🌟 Overview

**IronLink** is a specialized e-commerce platform designed for professional mechanics and performance tuners. Moving beyond simple listings, IronLink integrates **Augmented Reality (AR)** to verify part fitment and **Cloudflare Edge Workers** to ensure sub-100ms latency for real-time inventory tracking.

### Why IronLink?

- **Holographic Previews**: 3D/AR models for high-end components (Ducati, Suzuki, BMW).
- **The IronStack**: Built on the cutting-edge combination of Bun, Vite, and Supabase.
- **Neon-Dark UI**: A bespoke design system optimized for workshop environments.
- **Mechanic Support**: Live "Aviator" video support for complex installation queries.

## ✨ Features

### 🎯 Core Engineering
- **AR Fitment Engine**: View performance parts in 3D before purchasing.
- **Smart Tech Search**: Instant results filtered by Displacement (CC), Model Year, and SKU.
- **Role-Based Access (RBAC)**: Distinct interfaces for Users, Agents, and SuperAdmins.
- **Dynamic Pricing**: Real-time currency conversion and bulk-buy mechanic discounts.

### 🎨 UI/UX Aesthetic
- **Panigale Preloader**: A custom 2D-animated Ducati entrance sequence.
- **Glassmorphism**: Backdrop blurs and glowing cyan/orange borders (#00f0ff).
- **Holographic Cards**: 3D CSS credit card visualizer for secure checkouts.
- **Aviator Support**: Shrink-on-scroll glassmorphic support widget.

## 🛠️ Technologies Used

### Frontend & Design
- **React 18 + Vite**: Next-gen frontend tooling.
- **TanStack Router**: Type-safe routing for deep-linked product catalogs.
- **Framer Motion**: High-fidelity UI animations.
- **Three.js**: Powering the AR and 3D vehicle previews.

### Backend & DevOps
- **Bun**: Fast JavaScript runtime and package manager.
- **Supabase**: Managed PostgreSQL, Real-time subscriptions, and Edge Auth.
- **Cloudflare Wrangler**: Deploying serverless logic to the edge.
- **Drizzle ORM**: Type-safe database interactions.

## 📁 Project Structure

```text
IronLink/
│
├── .github/                # PR templates & CI/CD workflows
├── .tanstack/              # Auto-generated route trees
├── src/
│   ├── assets/             # 3D models (.glb), SVGs, and Panigale assets
│   ├── components/         # Atomic UI (Cards, Aviator, Navbar)
│   ├── hooks/              # Custom TanStack & Supabase hooks
│   ├── routes/             # File-based routing system
│   └── styles/             # Tailwind directives & Neon-Dark theme
│
├── supabase/               # SQL Migrations & Edge Functions
├── wrangler.jsonc          # Cloudflare configuration
├── bun.lockb               # Bun binary lockfile
└── tsconfig.json           # Strict-mode TypeScript config
```


## 📦 Vehicle Support Catalog

| Brand | Performance Category | Supported CC Range | Logic |
|-------|----------------------|--------------------|-------|
| **Ducati** | Superbike / Panigale | 955cc - 1103cc | Full AR |
| **Suzuki** | Dual-Sport / DR350 | 350cc - 650cc | Tech-Spec |
| **BMW** | Adventure / GS | 850cc - 1250cc | Full AR |
| **Honda** | Racing / CBR | 600cc - 1000cc | Tech-Spec |

## 🔮 Future Roadmap

- [ ] **IronVision 1.0**: Full mobile AR overlay using device cameras.
- [ ] **Crypto-Checkout**: Integrating Solana-based payments for international orders.
- [ ] **AI-Diagnose**: Image-recognition for identifying worn-out motorcycle parts.
- [ ] **Automated Telemetry**: Admin dashboard for real-time order heatmaps.

## 🤝 Collaborative Workflow

We use a formal **Jira-GitHub integration** to track every pull request.
1. **Assign**: Pick a ticket from the Jira Board.
2. **Branch**: `git checkout -b feat/IRON-XX-description`
3. **Commit**: `git commit -m "feat: [IRON-XX] implementation detail"`
4. **Review**: All code requires 1 approval from a Lead Engineer before merging.

## 👨‍💻 Lead Architects

- **J.M. Kalana Yasassri** - [GitHub](https://github.com/darkfeed2005) | [LinkedIn](https://www.linkedin.com/in/kalana-yasassri-684591251/)
- **Samath Lahiru** - [GitHub](https://github.com/darkfeed2005) | [LinkedIn](https://www.linkedin.com/in/kalana-yasassri-684591251/)

---
© 2026 IronLink Labs. Built for Performance.
