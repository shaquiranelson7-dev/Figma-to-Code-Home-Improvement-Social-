# Project Brief — Upmind

Auto-generated from Figma (`sdLaVofRVJRIdYko2En4hi`, node `1:178` "Home 1").

## Project

**Upmind** — a strategic growth / consulting marketing landing page. Single long-scroll home page with a five-step process showcase.

## Design Frame

- Frame width: **1280px** → `--size-container-ideal: 1280`
- Total height: ~10031px (long scroll)
- Container side padding: 52px (`3.25em` desktop)

## Brand Colors

| Token | Hex | Usage |
|-------|-----|-------|
| Primary / Accent | `#b7fe02` | Lime CTA buttons, accent text, highlights |
| Dark | `#101604` | Dark sections, dark buttons, hero/CTA backgrounds |
| White | `#ffffff` | Page background, text on dark |
| Text Primary | `#000000` | Headings on light |
| Text Secondary | `#595959` | Body copy on light |
| Border | `#e6e6e6` | Card borders, dividers |

## Typography

- **Headings & Body:** `Geist` (Google Fonts), weights 400–700
- **Mono / captions:** `Geist Mono` (Google Fonts)

Scale (Figma → CSS, line-height unitless, letter-spacing in px):

| Name | Size | Line-height | Letter-spacing |
|------|------|-------------|----------------|
| 6xl | 64px / 4em | 72 → 1.125 | -4px |
| 4xl | 48px / 3em | 56 → 1.167 | -4px |
| 2xl | 32px / 2em | 40 → 1.25 | -5px |
| xl | 24px / 1.5em | 32 → 1.333 | -4px |
| base | 16px / 1em | 24 → 1.5 | -2px |
| sm-cap (mono) | 14px / 0.875em | 20 → 1.429 | +12px |

## Spacing

Base scale of 4px (`spacing/0`=0, `spacing/1`=4, `spacing/2`=8 …). Section vertical rhythm ~72–100px.

## Border Radius

Cards and buttons use small-to-pill radii (extracted per-section in Phase 2). Pricing/feature cards ~16–24px; buttons ~8px / pill.

## Special Interactions

Static design — no animations specified. The "How We Work" area is a 5-step sequence (Strategic Audit → Action Roadmap → Guided Execution → Iteration & Metrics) rendered as stacked split-screen blocks. Logo strip in Partnership is a static row (no marquee animation unless requested).

## Component Patterns

Navbar, primary (lime) + dark buttons, eyebrow tag (dot + label), stat blocks, feature/service cards, pricing cards, blog cards, testimonial block, footer.

## Output

Framework: **Astro** (minimal template). Tokens written to `src/styles/global.css`. Layout: `src/layouts/BaseLayout.astro`.
