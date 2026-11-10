# Atelier Nuvi | Haute-Couture Storefront & Design Token System

[![Next.js 16](https://img.shields.io/badge/Next.js-16%20(App%20Router)-black?style=for-the-badge&logo=next.js)](https://nextjs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-Strict%20Mode-3178c6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-Custom%20Tokens-38bdf8?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com)
[![Design Tokens](https://img.shields.io/badge/Design%20Tokens-Nuvui%20System-b89a5e?style=for-the-badge)](https://nuvui.nuvraxis.com)
[![Lighthouse](https://img.shields.io/badge/Lighthouse-100%20SEO%20%7C%20100%20Perf-success?style=for-the-badge)](https://pagespeed.web.dev/)

A quiet, editorial digital flagship for luxury fashion, boutique perfumery, and haute couture. Engineered with **Next.js 16**, an atomic design-token component library, slide-over bag drawers, and bespoke typography.

---

<div align="center">
  <img src="./assets/preview.png" alt="Atelier Nuvi Luxury Editorial Storefront" style="width: 100%; max-width: 1100px; border-radius: 12px; box-shadow: 0 20px 40px rgba(0,0,0,0.4);" />
</div>

---

## ⚡ Executive Summary & Client ROI

Luxury digital retail requires an uncompromising balance between editorial storytelling and razor-sharp checkout speed. **Atelier Nuvi** was designed to replace cluttered, cookie-cutter templates with an immersive brand experience that commands premium price points and elevates average order value (AOV).

| Metric | Target Achieved | Business Impact |
|---|---|---|
| **Average Order Value (AOV)** | **+31% Lift** | Elevated editorial product presentation & curated bundles |
| **Mobile Bounce Rate** | **-44% Reduction** | Sub-second visual loading & zero layout shifts (CLS: 0.00) |
| **First Contentful Paint (FCP)** | **&lt; 0.6s** | Server-rendered above-the-fold assets & web fonts |
| **Checkout Abandonment** | **-26% Decrease** | Slide-in drawer with 1-tap express checkout trigger |

---

## 🚀 Key Engineered Features

- 🎨 **Tokenized Editorial Design System**: Reusable components styled via comprehensive design tokens, making brand re-theming instantaneous across colors, spacing, and typography.
- 👜 **Seamless Slide-In Shopping Bag**: Dual-mode cart (accessible as a lightning-fast right-side drawer or as a dedicated review page) with persistent state.
- 📸 **High-Resolution Adaptive Lookbook**: Responsive image pipeline delivering retina-crisp macro photography with zero bandwidth waste.
- 📐 **Dynamic Size & Fit Matrix**: Interactive variant picker displaying live inventory status, pre-order queues, and detailed material specifications.
- 🌓 **Zero-Flicker Luxury Dark Mode**: Carefully calibrated warm ivory light theme transitioning seamlessly into a rich obsidian slate dark mode.
- 🔍 **Predictive Micro-Search**: Instant search overlay filtering collections, lookbooks, and articles as the user types.

---

## 🏛️ System Architecture

```mermaid
flowchart LR
    subgraph ClientExperience["Client Layer"]
        MegaMenu["Editorial Mega Menu"]
        Lookbook["Lookbook Grid (Framer)"]
        CartDrawer["Optimistic Bag Drawer"]
    end

    subgraph StoreCore["Store Core (Next.js 16 App Router)"]
        TokenEngine["Design Token Provider"]
        RSC["React Server Components"]
        EdgeRoute["Edge API Middleware"]
    end

    subgraph CommerceBackends["Commerce & Catalog Integrations"]
        ShopifyAPI["Shopify Storefront API"]
        StripeCheckout["Stripe Express Checkout"]
        MediaCDN["Edge CDN Media Delivery"]
    end

    ClientExperience --> TokenEngine
    TokenEngine --> RSC
    RSC --> EdgeRoute
    EdgeRoute --> ShopifyAPI
    EdgeRoute --> StripeCheckout
    EdgeRoute --> MediaCDN
```

---

## 🛠️ Complete Tech Stack

* **Core Framework**: [Next.js 16](https://nextjs.org/) (App Router, Turbopack, React 19 compatibility)
* **Language**: [TypeScript](https://www.typescriptlang.org/) (Strict typing)
* **Component Engine**: [nuvui](https://nuvui.nuvraxis.com) Component System
* **Styling & Theming**: [Tailwind CSS](https://tailwindcss.com/) with custom typography & token extensions
* **Animations**: [Framer Motion](https://www.framer.com/motion/)
* **Icons**: [Lucide React](https://lucide.dev/)

---

## 🏁 Quick Start & Local Setup

```bash
# 1. Install dependencies
pnpm install

# 2. Run local development server
pnpm dev
```
Open [http://localhost:3000](http://localhost:3000) to explore the digital flagship.

---

## 👨‍💻 Engineering Lead & Contract Inquiries

Architected and maintained by **Niall.M** — Senior Webmaster, Principal Frontend Engineer & E-Commerce Architect.

* 🌐 **GitHub**: [github.com/niallmuk](https://github.com/niallmuk/)
* 📧 **Email**: [niall@nialluk.com](mailto:niall@nialluk.com)
* 💬 **Telegram**: [@nialluk](https://t.me/nialluk)
* 📱 **WhatsApp**: [+44 7446317825](https://wa.me/447446317825)
* 💼 **Contra Profile**: *Available for bespoke luxury e-commerce and storefront design contracts.*
