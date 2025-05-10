# 🛏️ Case Study: Tariff-Free Sheets Landing Page (SvelteKit)

This is a pixel-perfect, responsive landing page built for a UI/UX test task by Novus Studio. The page replicates a Figma design using clean semantic HTML, scoped CSS, and SvelteKit best practices with a strong focus on performance, maintainability, and design accuracy.

---

## 🚀 Live Preview

**[🔗 View Deployed Site (Vercel)](https://novus-studio-sveltekit.vercel.app)**  
**📂 [View Code on GitHub](https://github.com/AJ-logic/novus-studio-sveltekit)**

---

## 📦 Stack & Tools

- **Framework**: [SvelteKit](https://kit.svelte.dev/)
- **Language**: HTML, CSS (scoped), JavaScript
- **Fonts**: Brandon Grotesque (`.woff2`, self-hosted)
- **Image Optimization**: `.webp`, compressed with [Squoosh](https://squoosh.app)
- **Deployment**: [Vercel](https://vercel.com/)

---

## 📱 Responsiveness

- ✅ Mobile (414px)
- ✅ Desktop (1440px max-width container)
- Components are fully responsive and tested across breakpoints.

---

## 📈 Lighthouse Scores (Mobile)

| Category       | Score |
| -------------- | ----- |
| Performance    | 95+   |
| Accessibility  | 95+   |
| Best Practices | 100   |
| SEO            | 100   |

---

## ✨ Highlights

- **1:1 match with Figma** — Font sizing, spacing, layout all faithfully reproduced.
- **Componentized architecture** — Hero, Reason blocks, CTA, Footer, etc.
- **LCP Optimized** — Priority-loaded first visible image with `loading="eager"` and `fetchpriority="high"`.
- **Fonts & Images Optimized** — All assets served in production-ready format.

---

## 🧠 Developer Notes

- Fonts loaded via `@font-face` using `.woff2` with `font-display: swap`.
- `<meta>` tags include SEO-friendly description, Open Graph, and Twitter cards.
- `loading="lazy"` added to all non-critical images.
- `width` and `height` set for all `<img>` elements to avoid layout shifts.
- `HeroSection`, `ReasonSection`, and `CTASection` are isolated Svelte components.
- Centralized content via a `reasons.js` data file with props passed into reusable `ReasonSection`.

---

## 🛠 Setup & Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/AJ-logic/novus-studio-sveltekit.git

# 2. Navigate to the project
cd novus-studio-sveltekit

# 3. Install dependencies
npm install

# 4. Run locally
npm run dev
```
