# Site Map — Upmind

**Figma File Key**: `sdLaVofRVJRIdYko2En4hi`
**Source URL**: `https://www.figma.com/design/sdLaVofRVJRIdYko2En4hi/upmind?node-id=1-178&m=dev`
**Container Max-Width**: `1280px` (frame width)

## Pages

### Page: Home
Node ID: `1:178` (frame "Home 1", 1280 × 10031)

#### Sections

| Section | Node ID | Component | Background | Notes |
|---------|---------|-----------|------------|-------|
| Navbar | `3475:1368` | Navbar.astro | transparent over hero | Shared; logo + nav links + CTA |
| Hero | `3475:1365` | Hero.astro | dark bg image | Title, subtitle, 2 buttons, floating AI label buttons |
| Partnership | `1:265` | Partnership.astro | white | Tag, title, 3 stats, partner logo row |
| About Us | `1:350` | AboutUs.astro | white | Tag, title, subtitle, button + stat/tag visual card |
| Services | `1:396` | Services.astro | white | Tag, title, subtitle, button + 3 service cards |
| How We Work | `1:441` | HowWeWork.astro | split light/image | Step 1 + steps `257:1365`, `257:1421`, `257:1448`, `257:1469` (5-step process) |
| Testimonials | `1:461` | Testimonials.astro | white | Tag, quote, author, prev/next buttons |
| Pricing | `1:481` | Pricing.astro | white | Tag, title, 2 pricing cards |
| Blogs | `1:553` | Blogs.astro | white | Tag, title, subtitle + 4 article cards |
| CTA | `1:584` | CTA.astro | dark bg image | Title, subtitle, 2 buttons |
| Footer | `2:5448` | Footer.astro | dark | Footer component instance |

## How We Work — step node IDs

| Step | Node ID | Title (from layer names) |
|------|---------|--------------------------|
| 1 | `1:441` | (step 1 — confirm via design context) |
| 2 | `257:1365` | Strategic Audit |
| 3 | `257:1421` | Action Roadmap |
| 4 | `257:1448` | Guided Execution |
| 5 | `257:1469` | Iteration & Metrics |

## Shared Components

| Component | Node ID | Description |
|-----------|---------|-------------|
| Navbar | `3475:1368` | Top navigation, transparent over hero |
| Button (primary lime) | `3475:1374` | Lime `#b7fe02` filled button |
| Button (dark) | `3475:1378` | Dark `#101604` button |
| Tag / eyebrow | `1:267` | Dot + uppercase label |
| Footer | `2:5448` | Site footer |

## Layout Notes

- Every section: full-width background, content capped at 1280px, side padding `--container-padding`.
- Hero & CTA use full-bleed background images with light text.
- Partnership/About/Services/Pricing/Blogs are light sections on white.
