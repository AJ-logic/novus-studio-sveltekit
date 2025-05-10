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

- Fonts loaded via `@font-face` using `.woff2` with `font-display: swap`.
- `<meta>` tags include SEO-friendly description, Open Graph, and Twitter cards.
- `loading="lazy"` added to all non-critical images.
- `width` and `height` set for all `<img>` elements to avoid layout shifts.
- `HeroSection`, `ReasonSection`, and `CTASection` are isolated Svelte components.
- Centralized content via a `reasons.js` data file with props passed into reusable `ReasonSection`.
- **No duplicated markup** for mobile/desktop; layout is handled with CSS flexbox and media queries.

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

---

## 🤝 Contributing

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 🙏 Credits

- [SvelteKit](https://kit.svelte.dev/)
- [Figma](https://figma.com/)
- [Novus Studio](https://novus.studio/)

---

## 📬 Contact

For questions, feedback, or collaboration, please contact [your-email@example.com](mailto:your-email@example.com).

---

> **Happy coding! 🚀**
