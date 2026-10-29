# Lumen & Co. — Event Agency Landing Page (Design Study)

A one-page landing site for **Lumen & Co.**, a fictional premium event agency. I built it as a portfolio and practice project to study how a modern editorial agency site is put together: its design system, layout, and scroll-driven motion.

> Not affiliated with any real company. The brand, copy and client names are original and fictional. The layout and motion approach were studied from public agency sites, including iventions.com, but no logos, text, video or other assets from those sites are used.

## Features
- Fluid `rem` grid: 1rem = 10px on the design canvas (375 / 768 / 1920), scaled with `vw` at breakpoints of 768px and 1200px
- Warm-paper and soft-ink palette with a lime accent and pastel service colours
- Loader with a counter, plus a curtain-style page transition
- Three-column header and a full-screen menu that opens as a circle reveal
- Pinned hero that expands from a rounded box to full screen, with animated light beams
- A statement that lights up word by word as you scroll
- Project slider with clip-path wipes and masked title swaps (drag, swipe and keyboard all work)
- Infinite client marquee and photo strip
- Sticky service panels that stack as you scroll
- Parallax CTA and a full-width footer wordmark
- Custom cursor on desktop; animations respect `prefers-reduced-motion`
- Responsive layouts for mobile, tablet and desktop

## Tech
Plain HTML, CSS and JS in a single `index.html`. GSAP 3 + ScrollTrigger and Lenis load from a CDN, and the page still works without them. Fonts are Inter Tight and Instrument Serif from Google Fonts.

## Run locally
```bash
git clone https://github.com/VorynixbyHasan/harks-ai-agent-clone-website-invention-.git
cd harks-ai-agent-clone-website-invention-
npx serve .          # or: python -m http.server 8080
```
Then open http://localhost:3000 (or http://localhost:8080).

## Photo credits
Free-licence photos from [Unsplash](https://unsplash.com/license) and [Pixabay](https://pixabay.com/service/license-summary/), in `images/`.

## Author
Hasan Zai (Vorynix). Portfolio practice project, not for commercial use.
