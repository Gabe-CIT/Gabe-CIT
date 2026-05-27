---
name: Gabe-CIT Profile · Liquid Tech
description: A "liquid glass" GitHub profile README rendered as a stack of self-contained SVG cards. Each card uses the foreignObject technique to host real HTML/CSS — including backdrop-filter blur — inside an image that GitHub will serve. The system adapts to the viewer's OS color scheme via prefers-color-scheme: light is canonical (the YAML values below), dark overrides via the pairing table in the Colors prose. The single brand voltage is a lavender-indigo accent (#5e6ad2 light / #7c83ff dark) used sparingly on eyebrows, tier pips, and the terminal cursor — never decoratively. The hero is the only card with a colorful gradient orb behind the glass; the rest sit on the canvas as frosted glass panels. Inter for display and body, JetBrains Mono for code surfaces and eyebrow labels — the techy detail that ties the system together.

colors:
  canvas: "#fafafa"
  canvas-soft: "#f5f5f5"

  surface-glass: "rgba(0, 0, 0, 0.035)"
  surface-glass-elevated: "rgba(0, 0, 0, 0.05)"

  hairline: "rgba(0, 0, 0, 0.10)"
  hairline-strong: "rgba(0, 0, 0, 0.14)"
  hairline-shine: "rgba(255, 255, 255, 0.70)"

  on-canvas: "#1a1a1f"
  on-canvas-muted: "#5a5a64"
  on-canvas-subtle: "#8a8a92"

  primary: "#5e6ad2"
  primary-deep: "#4751b8"
  primary-soft: "rgba(94, 106, 210, 0.20)"
  on-primary: "#ffffff"

  gradient-1: "#2563eb"
  gradient-2: "#9333ea"
  gradient-3: "#ec4899"

  accent-python: "#3776ab"
  accent-javascript: "#f7df1e"
  accent-git: "#f05032"
  accent-shell: "#4eaa25"
  accent-windows: "#0078d4"
  accent-troubleshoot: "#d29922"

  error: "#ff6161"
  success: "#59d499"

typography:
  display:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
    fontSize: 64px
    fontWeight: "600"
    lineHeight: 1.05
    letterSpacing: -2px
  headline:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
    fontSize: 24px
    fontWeight: "600"
    lineHeight: 1.2
    letterSpacing: -0.4px
  title:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
    fontSize: 18px
    fontWeight: "500"
    lineHeight: 1.4
  eyebrow:
    fontFamily: "'JetBrains Mono', ui-monospace, 'SF Mono', Menlo, monospace"
    fontSize: 11px
    fontWeight: "500"
    lineHeight: 1.4
    letterSpacing: 0.16em
  body-lg:
    fontFamily: "Inter, -apple-system, sans-serif"
    fontSize: 16px
    fontWeight: "400"
    lineHeight: 1.6
  body:
    fontFamily: "Inter, -apple-system, sans-serif"
    fontSize: 14px
    fontWeight: "400"
    lineHeight: 1.5
  body-strong:
    fontFamily: "Inter, -apple-system, sans-serif"
    fontSize: 14px
    fontWeight: "600"
    lineHeight: 1.5
  caption:
    fontFamily: "Inter, -apple-system, sans-serif"
    fontSize: 12px
    fontWeight: "400"
    lineHeight: 1.5
  code:
    fontFamily: "'JetBrains Mono', ui-monospace, 'SF Mono', Menlo, monospace"
    fontSize: 13px
    fontWeight: "400"
    lineHeight: 1.5

rounded:
  sm: 8px
  md: 12px
  lg: 16px
  xl: 24px
  full: 9999px

spacing:
  unit: 4px
  card-padding-x: 32px
  card-padding-y: 28px
  card-gap: 20px
  grid-gap: 16px
  pill-padding-x: 16px
  pill-padding-y: 14px

components:
  card-glass:
    backgroundColor: "{colors.surface-glass}"
    textColor: "{colors.on-canvas}"
    rounded: "{rounded.lg}"
    padding: 28px 32px
    width: 850px

  card-hero:
    backgroundColor: "{colors.surface-glass-elevated}"
    textColor: "{colors.on-canvas}"
    rounded: "{rounded.xl}"
    padding: 0 48px
    width: 850px
    height: 280px

  card-about:
    backgroundColor: "{colors.surface-glass}"
    textColor: "{colors.on-canvas}"
    rounded: "{rounded.lg}"
    padding: 28px 32px
    width: 850px
    height: 200px

  card-skills:
    backgroundColor: "{colors.surface-glass}"
    textColor: "{colors.on-canvas}"
    rounded: "{rounded.lg}"
    padding: 28px 32px
    width: 850px
    height: 280px

  card-learning:
    backgroundColor: "{colors.surface-glass}"
    textColor: "{colors.on-canvas}"
    rounded: "{rounded.lg}"
    padding: 24px 32px
    width: 850px
    height: 200px

  card-projects:
    backgroundColor: "{colors.surface-glass}"
    textColor: "{colors.on-canvas}"
    rounded: "{rounded.lg}"
    padding: 24px 32px
    width: 850px
    height: 200px

  card-contact:
    backgroundColor: "{colors.surface-glass}"
    textColor: "{colors.on-canvas}"
    rounded: "{rounded.lg}"
    padding: 28px 32px
    width: 850px
    height: 160px

  eyebrow-label:
    textColor: "{colors.primary}"
    typography: "{typography.eyebrow}"

  card-title:
    textColor: "{colors.on-canvas}"
    typography: "{typography.headline}"

  card-subtitle:
    textColor: "{colors.on-canvas-muted}"
    typography: "{typography.body}"

  skill-pill:
    backgroundColor: "{colors.surface-glass-elevated}"
    textColor: "{colors.on-canvas}"
    typography: "{typography.body-strong}"
    rounded: "{rounded.md}"
    padding: 14px 16px

  skill-pill-dot:
    rounded: "{rounded.full}"
    height: 10px
    width: 10px

  tier-pip-active:
    backgroundColor: "{colors.primary}"
    rounded: "{rounded.full}"
    height: 6px
    width: 6px

  tier-pip-inactive:
    backgroundColor: "{colors.hairline-strong}"
    rounded: "{rounded.full}"
    height: 6px
    width: 6px

  learning-item:
    backgroundColor: "{colors.surface-glass-elevated}"
    textColor: "{colors.on-canvas}"
    rounded: "{rounded.md}"
    padding: 14px 16px

  pulse-indicator:
    backgroundColor: "{colors.primary}"
    rounded: "{rounded.full}"
    height: 10px
    width: 10px

  contact-cursor:
    backgroundColor: "{colors.primary}"
    height: 18px
    width: 9px

  badge-link:
    backgroundColor: "{colors.surface-glass-elevated}"
    textColor: "{colors.on-canvas}"
    rounded: "{rounded.full}"
    typography: "{typography.code}"
    height: 36px
    padding: 0 18px
---

## Overview

The Gabe-CIT profile README is a stack of self-contained SVG cards
that share one aesthetic: **liquid glass on near-black**. Each card
ships as a single SVG file using `<foreignObject>` to host HTML and
CSS, which lets the cards render real backdrop blur, gradients, and
animations inside an image GitHub will gladly serve as part of the
README.

The visual identity is **modern + techy**, drawing from three
references: Linear's near-black surface ladder and surgical use of
lavender-indigo, Raycast's hairline 1px borders and command-palette
chrome, and Google Labs' Atmospheric Glass for the backdrop-filter
glass stack. JetBrains Mono carries the techy detail on three
surfaces — eyebrow labels, terminal cursor surroundings, and stat
numbers — while Inter handles display and body.

**The system adapts to the viewer's OS color scheme via
`prefers-color-scheme`.** Light mode is canonical (the YAML values
above describe it); dark mode overrides via the pairing table in
the Colors section. The same SVG files morph based on the viewer's
operating-system theme preference — note this follows the OS,
**not** GitHub's site theme toggle.

The hero is the only card carrying a colorful gradient (a multi-stop
orb of blue, purple, and pink, blurred behind the glass). Every
other card is frosted glass on the canvas. The hero gets the wow;
the rest get rhythm.

## Colors

Light mode is canonical (the YAML values above). Dark mode overrides
via `@media (prefers-color-scheme: dark)` inside each SVG's
`<style>` block. The same SVG file renders in either palette
depending on the viewer's OS preference.

### Light / dark pairing table

| Token | Light (default) | Dark (override) |
|---|---|---|
| `canvas` | `#fafafa` | `#07080a` |
| `canvas-soft` | `#f5f5f5` | `#0d0d10` |
| `surface-glass` | `rgba(0, 0, 0, 0.035)` | `rgba(255, 255, 255, 0.045)` |
| `surface-glass-elevated` | `rgba(0, 0, 0, 0.05)` | `rgba(255, 255, 255, 0.07)` |
| `hairline` | `rgba(0, 0, 0, 0.10)` | `rgba(255, 255, 255, 0.08)` |
| `hairline-strong` | `rgba(0, 0, 0, 0.14)` | `rgba(255, 255, 255, 0.14)` |
| `hairline-shine` | `rgba(255, 255, 255, 0.70)` | `rgba(255, 255, 255, 0.18)` |
| `on-canvas` | `#1a1a1f` | `#f4f4f6` |
| `on-canvas-muted` | `#5a5a64` | `#a4a8b0` |
| `primary` | `#5e6ad2` | `#7c83ff` |
| `primary-soft` | `rgba(94, 106, 210, 0.20)` | `rgba(124, 131, 255, 0.30)` |
| `gradient-1` | `#2563eb` | `#1e3a8a` |
| `gradient-2` | `#9333ea` | `#7e22ce` |
| `gradient-3` | `#ec4899` | `#db2777` |

**Glass surfaces** use semi-transparent fills with
`backdrop-filter: blur(24px) saturate(140%)` applied. The same
property values work in both modes — only the alpha-tinted RGB
values change (white-tinted on dark canvas, black-tinted on light
canvas).

**Hairline shine** is the standout asymmetry: on light mode it's
nearly opaque white (`0.70`) because the inset top edge of a glass
panel against a light canvas needs more contrast to read as a light
catch. On dark it's a subtle `0.18` because the surrounding glass
is already light enough to make the edge pop.

**Brand voltage** (`primary`) appears only on:

- Eyebrow labels (`// section_name` style)
- Active tier pips on the skills card
- The blinking terminal cursor in `card-contact`
- The hero accent underline
- The `→` arrow in the contact subtitle

The accent is paired with `primary-soft` as a glow shadow on the
underline, cursor, and active pips so the lavender feels luminous,
not painted on.

**Hero gradient orb** uses three stops, animated to drift slowly.
The dark-mode hex values shift slightly to deeper, more saturated
versions for visual richness against the near-black canvas; the
light-mode values stay brighter so the orb still pops through a
white frosted glass.

**Skill category accents** are kept as the brand colors of each
technology (Python blue, JavaScript yellow, Git orange, etc.) —
identical in both modes. The dot glow (`box-shadow: 0 0 8px
currentColor`) gives each dot a small colored aura that reads on
both light and dark surfaces.

## Typography

Two families, one job each.

- **Inter** carries every prose surface. Display, headline, title,
  body, captions. It's the modern techy default because it's neutral
  enough to disappear, and because nearly every viewer's browser
  has it cached from some other site. We use weights 400 / 500 / 600
  only; no 700+ — heavy weights fight the glass aesthetic.

- **JetBrains Mono** carries two specific surfaces:
  - Eyebrow labels at the top of each card (`// SECTION_NAME` style)
  - The kind-labels inside `card-projects` (`BUILDING →` etc.)

These are deliberate techy notes. Monospace is the costume the
system puts on for those moments, and only those moments. Don't
extend it to general body copy — the page becomes a Visual Studio
Code screenshot.

Tracking is **negative on display and headline** (-2px and -0.4px
respectively) so the type feels tight and confident. Eyebrow labels
go the opposite direction (+0.16em / 0.16 of the font's em-width) so
they read as labels, not microscopic body text.

## Layout & Spacing

All cards are **850px wide**, stacked vertically with 20px
(`spacing.card-gap`) between them. The README markdown renders each
card with `width="100%"` so the browser scales them down on narrow
viewports.

Card heights follow a **three-step scale** — no exceptions:

| Height | Use | Cards |
|---|---|---|
| 160px | Single thought | `card-contact` |
| 200px | Standard | `card-about`, `card-learning`, `card-projects` |
| 280px | Dense / hero | `card-skills`, `card-hero` |

Internal padding is **24-28px top/bottom, 32px left/right** for
standard cards. The hero is the exception — 48px horizontal padding
because the display-size name visually crowds at 32px.

Grids inside cards use a **12px gap** (`spacing.grid-gap`):

- `card-skills`: 3 columns × 2 rows of `skill-pill`
- `card-learning`: 3 columns × 1 row of `learning-item`
- `card-projects`: 3 columns × 1 row (Building / Learning / Curious about)

The README stacks cards in a single column. Side-by-side card
layouts aren't used — markdown's image wrappers don't reliably
support flex/grid, and column layouts collapse on mobile anyway.

## Elevation & Depth

Depth comes from **light refraction and blur**, not shadow. There is
exactly one shadow in the system (a soft, spread-out lift under each
card) and it's there to separate the panel from the canvas, not to
imply altitude.

**The glass stack:**

- **Level 0 (canvas)** — `canvas` (`#fafafa` light / `#07080a` dark)
  rendered inside each SVG as a backing rect so the glass has
  something to refract. The README markdown's own background sits
  *behind* the SVG canvas — we don't depend on it.
- **Level 1 (card glass)** — `surface-glass` with `backdrop-filter:
  blur(24px) saturate(140%)`, 1px `hairline` border, plus a 1px
  inset top edge in `hairline-shine` for the refraction "catch".
- **Level 2 (nested glass)** — `surface-glass-elevated`. Skill pills,
  learning items, project items. Slightly higher alpha so they lift
  off the card's own glass without needing a shadow.

No drop shadows. The system stays flat; depth comes from blur and
the top-edge shine.

## Shapes

Four rounded scale steps plus a `full` pill:

- **`rounded.sm`** (8px) — badge links, small interactive elements.
- **`rounded.md`** (12px) — nested items inside cards (skill pills,
  learning items).
- **`rounded.lg`** (16px) — every standard card.
- **`rounded.xl`** (24px) — the hero only. Slightly more rounded
  than the rest because the hero is the most "liquid" card.
- **`rounded.full`** — circular dots (skill dots, tier pips, pulse
  indicator) and the contact badges (lozenge pills).

No square corners. No diamond shapes. No irregular radii on a single
element. The shape language is calm by intent.

## Components

### `card-hero` (280px)

The signature card. Renders as a glass panel sitting over a multi-
stop gradient orb (`gradient-1` / `gradient-2` / `gradient-3`)
animated to drift slowly across the canvas. The orb is a `<rect>`
fill inside the SVG; the glass panel is the foreignObject HTML
sitting on top with `backdrop-filter: blur(36px)`.

Content: eyebrow `// hello`, display-size name, title-size role
line, and a 120px lavender underline (`primary`) that grows in on
load. The waving hand is its own inline span with a rotation
animation; everything else fades up in a 0.2–0.8s staggered cascade.

### `card-about` (200px)

Eyebrow `// ABOUT` + headline `Who I am` + a 4-line body-lg
paragraph. No gradient, no decoration — the prose is the content.
Glass panel on canvas.

### `card-skills` (280px)

Eyebrow `// STACK` + headline `Tech stack` + a 3×2 grid of
`skill-pill`. Each pill contains:

- An 8px `skill-pill-dot` in the technology's brand color, with a
  `box-shadow: 0 0 8px currentColor` aura so the dot glows.
- A `body-strong` label (technology name).
- Five vertical-bar `tier-pip` indicators on the right edge (4×12px
  each, `border-radius: 2px`) — the first N filled with `primary`
  (lavender, with a `primary-soft` glow), the rest in
  `hairline-strong`. Reads almost like a signal-strength meter.
  Replaces the inconsistent text labels from the previous design.

Recommended tier values:

| Skill | Tier (filled pips of 5) |
|---|---|
| Python | 4 |
| JavaScript | 2 |
| Git | 3 |
| Shell / CLI | 3 |
| Windows admin | 2 |
| Troubleshooting | 4 |

Pills enter with a 0.05s-staggered rise-in animation (gated behind
`prefers-reduced-motion`).

### `card-learning` (200px)

Eyebrow `// IN_PROGRESS` + a `pulse-indicator` (lavender 8px dot with
expanding `primary-soft` ring) next to the headline `Currently
learning`. Three `learning-item` blocks in a 3-column grid; each
item has a `body-strong` headline and a caption-sized "why" line.
Each item has a 3px left border in `primary` lavender for category
emphasis.

### `card-projects` (200px)

Eyebrow `// ACTIVE` + headline `What I'm on right now` + a 3-column
strip of items, each with a small monospace kind-label
(`BUILDING →`, `LEARNING →`, `CURIOUS ABOUT →`) above the content.
Sits between learning and contact.

Content uses `{BUILDING}`, `{LEARNING}`, `{CURIOUS}` placeholders
that Gabriel fills before pushing. Update as work shifts.

### `card-contact` (160px)

Eyebrow `// reach_out` + headline `Find me here` with a blinking
`contact-cursor` (lavender 9×18px block, `steps(2, start)` animation)
inline after the headline. A `body` subtitle, then three `badge-link`
subtitle inviting contact, with an `→` arrow in `primary` lavender.

Clickable links are not inside the SVG — they sit in the README
markdown directly below the card as shields.io badges (SVG-as-`<img>`
doesn't receive pointer events). The badges use a near-black
background with `7c83ff` logo color so they match the system.

## Do's and Don'ts

**Do:**

- Use the `primary` lavender accent only on the surfaces listed in
  the Colors section. Decorative use kills its signature value.
- Apply `backdrop-filter: blur(24px) saturate(140%)` on every glass
  panel. Both properties together — saturate compensates for the
  desaturation that blur causes.
- Add a 1px inset top border in `hairline-shine` to every card's
  CSS. It's a single line of code that does more for the
  glass aesthetic than any other detail.
- Gate every animation behind `@media (prefers-reduced-motion:
  reduce)`. Accessibility, not optional.
- Use JetBrains Mono only on the sanctioned surfaces (eyebrow labels
  and the projects-card kind-labels). Anywhere else is leakage.
- Test in a browser before pushing. GitHub aggressively caches SVG
  through Camo; if you don't see your change, append `?v=2` to the
  image URL.

**Don't:**

- Don't replicate the hero gradient on any other card. The hero is
  the moment; the rest is rhythm.
- Don't use `:hover`, `:focus`, `:active`, or any interactive
  pseudo-class. The SVGs are served as `<img>` and receive no
  pointer events. Animation must run on a timer, not on input.
- Don't add JavaScript inside the SVG. GitHub's image sandbox
  blocks it.
- Don't reference external fonts via `@font-face` or external
  stylesheets. The SVG must be self-contained. If Inter or
  JetBrains Mono isn't available locally, the system font stack
  fallback handles it gracefully.
- Don't introduce card heights outside the **160 / 200 / 280**
  scale. Rhythm beats variety.
- Don't put load-bearing information in fonts smaller than 12px.
  SVGs scale down on mobile and small captions become unreadable.
