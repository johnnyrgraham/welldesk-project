# WellDesk — Mobile Concepts (v1)

Three mobile landing-page concepts for the WellDesk pre-order launch, shown as
side-by-side scrollable phone mockups. Built as a static site — no build step,
no dependencies.

## Contents
- `index.html` — the presentation page (Options A, B, C)
- `images/` — web-optimised product photography
  - `hero.jpg` — lifestyle render (hero-grade)
  - `standing.jpg`, `seated.jpg`, `sunlit.jpg` — real prototype shots

## Make it live
Any static host works:
- **Vercel:** `npx vercel` from this folder, or drag the folder into vercel.com/new
- **Netlify:** drag the folder onto app.netlify.com/drop
- **GitHub Pages:** push the folder to a repo, enable Pages on the root

## Notes
- All prices, dates, and specs are intentional `[INSERT]` placeholders pending
  client confirmation — fill before any public share beyond the client review.
- Fonts load from Google Fonts (Outfit + Inter) with system fallbacks.
- Option B's product image cross-fades via IntersectionObserver as its chapters
  scroll; respects `prefers-reduced-motion`.
- Photography is placeholder-grade (prototype shots + one render). The chosen
  direction should get a proper lifestyle shoot before launch.
