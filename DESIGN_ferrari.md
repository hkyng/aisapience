version: alpha
name: Ferrari-design-analysis
description: A luxury-automotive brand whose marketing surfaces read as cinematic editorial. The base canvas is near-black (#181818) holding pure white display type; white-canvas bands appear only inside specific editorial contexts (preowned listings, pricing tables). The single brand voltage is Rosso Corsa (#da291c) — the iconic Ferrari racing red — used scarcely on primary CTAs, the Cavallino mark, and Formula 1 race-position highlights. Type runs FerrariSans at modest weights (display 500, body 400) — never bombastic. Spacing follows an explicit 8px token ladder (xxxs 4px through super 128px); generous editorial pacing throughout. The brand's strongest visual signature is the full-bleed cinematic hero photograph that fills the viewport top with car photography, model details, or trackside livery — followed by a tighter editorial body layout below.

colors:
  primary: "#da291c"
  primary-active: "#b01e0a"
  primary-hover: "#9d2211"
  ink: "#ffffff"
  body: "#969696"
  body-strong: "#ffffff"
  body-on-light: "#181818"
  muted: "#666666"
  muted-soft: "#8f8f8f"
  hairline: "#303030"
  hairline-on-light: "#d2d2d2"
  hairline-soft: "#ebebeb"
  canvas: "#181818"
  canvas-elevated: "#303030"
  canvas-light: "#ffffff"
  surface-card: "#303030"
  surface-soft-light: "#f7f7f7"
  surface-strong-light: "#ebebeb"
  on-primary: "#ffffff"
  on-dark: "#ffffff"
  on-light: "#181818"
  accent-yellow-hypersail: "#fff200"
  accent-yellow: "#f6e500"
  semantic-info: "#4c98b9"
  semantic-success: "#03904a"
  semantic-warning: "#f13a2c"

typography:
  display-mega: { fontFamily: "'FerrariSans', -apple-system, system-ui, sans-serif", fontSize: 80px, fontWeight: 500, lineHeight: 1.05, letterSpacing: -1.6px }
  display-xl: { fontFamily: "'FerrariSans', sans-serif", fontSize: 56px, fontWeight: 500, lineHeight: 1.1, letterSpacing: -1.12px }
  display-lg: { fontFamily: "'FerrariSans', sans-serif", fontSize: 36px, fontWeight: 500, lineHeight: 1.2, letterSpacing: -0.36px }
  display-md: { fontFamily: "'FerrariSans', sans-serif", fontSize: 26px, fontWeight: 500, lineHeight: 1.5, letterSpacing: 0.195px }
  title-md: { fontFamily: "'FerrariSans', sans-serif", fontSize: 18px, fontWeight: 700, lineHeight: 1.2, letterSpacing: 0 }
  title-sm: { fontFamily: "'FerrariSans', sans-serif", fontSize: 16px, fontWeight: 500, lineHeight: 1.4, letterSpacing: 0.08px }
  body-md: { fontFamily: "'FerrariSans', sans-serif", fontSize: 14px, fontWeight: 400, lineHeight: 1.5, letterSpacing: 0 }
  body-sm: { fontFamily: "'FerrariSans', sans-serif", fontSize: 13px, fontWeight: 400, lineHeight: 1.5, letterSpacing: 0 }
  caption: { fontFamily: "'FerrariSans', sans-serif", fontSize: 12px, fontWeight: 400, lineHeight: 1.4, letterSpacing: 0 }
  caption-uppercase: { fontFamily: "'FerrariSans', sans-serif", fontSize: 11px, fontWeight: 600, lineHeight: 1.4, letterSpacing: 1.1px, textTransform: uppercase }
  button: { fontFamily: "'FerrariSans', sans-serif", fontSize: 14px, fontWeight: 700, lineHeight: 1.0, letterSpacing: 1.4px, textTransform: uppercase }
  nav-link: { fontFamily: "'FerrariSans', sans-serif", fontSize: 13px, fontWeight: 600, lineHeight: 1.4, letterSpacing: 0.65px, textTransform: uppercase }
  number-display: { fontFamily: "'FerrariSans', sans-serif", fontSize: 80px, fontWeight: 700, lineHeight: 1.0, letterSpacing: -1.6px }

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 6px
  lg: 8px
  xl: 12px
  full: 9999px

spacing:
  xxxs: 4px
  xxs: 8px
  xs: 16px
  sm: 24px
  md: 32px
  lg: 48px
  xl: 64px
  xxl: 96px
  super: 128px

components:
  top-nav-on-dark: { backgroundColor: "{colors.canvas}", textColor: "{colors.ink}", typography: "{typography.nav-link}", height: 64px }
  top-nav-on-light: { backgroundColor: "{colors.canvas-light}", textColor: "{colors.body-on-light}", typography: "{typography.nav-link}", height: 64px }
  button-primary: { backgroundColor: "{colors.primary}", textColor: "{colors.on-primary}", typography: "{typography.button}", rounded: "{rounded.none}", padding: 14px 32px, height: 48px }
  button-primary-active: { backgroundColor: "{colors.primary-active}", textColor: "{colors.on-primary}", rounded: "{rounded.none}" }
  button-outline-on-dark: { backgroundColor: transparent, textColor: "{colors.ink}", typography: "{typography.button}", rounded: "{rounded.none}", padding: 13px 31px, height: 48px }
  button-outline-on-light: { backgroundColor: transparent, textColor: "{colors.body-on-light}", typography: "{typography.button}", rounded: "{rounded.none}", padding: 13px 31px, height: 48px }
  button-tertiary-text: { backgroundColor: transparent, textColor: "{colors.ink}", typography: "{typography.button}" }
  hero-band-cinema: { backgroundColor: "{colors.canvas}", textColor: "{colors.ink}", typography: "{typography.display-mega}", padding: 0 }
  hero-band-light: { backgroundColor: "{colors.canvas-light}", textColor: "{colors.body-on-light}", typography: "{typography.display-xl}", padding: 96px }
  feature-card-photo: { backgroundColor: "{colors.canvas}", textColor: "{colors.ink}", typography: "{typography.title-md}", rounded: "{rounded.none}", padding: 0 }
  feature-card-light: { backgroundColor: "{colors.canvas-light}", textColor: "{colors.body-on-light}", typography: "{typography.title-md}", rounded: "{rounded.none}", padding: 32px }
  livery-band: { backgroundColor: "{colors.primary}", textColor: "{colors.ink}", typography: "{typography.display-lg}", padding: 96px }
  preowned-listing-card: { backgroundColor: "{colors.canvas-light}", textColor: "{colors.body-on-light}", typography: "{typography.body-md}", rounded: "{rounded.none}", padding: 24px }
  spec-cell: { backgroundColor: transparent, textColor: "{colors.ink}", typography: "{typography.number-display}", padding: 24px 0 }
  race-position-cell: { backgroundColor: transparent, textColor: "{colors.primary}", typography: "{typography.number-display}" }
  race-calendar-row: { backgroundColor: transparent, textColor: "{colors.ink}", typography: "{typography.body-md}", padding: 16px 0 }
  driver-card: { backgroundColor: "{colors.canvas-elevated}", textColor: "{colors.ink}", typography: "{typography.title-md}", rounded: "{rounded.none}", padding: 24px }
  text-input-on-dark: { backgroundColor: "{colors.canvas}", textColor: "{colors.ink}", typography: "{typography.body-md}", rounded: "{rounded.sm}", padding: 14px 16px, height: 48px }
  text-input-on-light: { backgroundColor: "{colors.canvas-light}", textColor: "{colors.body-on-light}", typography: "{typography.body-md}", rounded: "{rounded.sm}", padding: 14px 16px, height: 48px }
  badge-pill: { backgroundColor: "{colors.canvas-elevated}", textColor: "{colors.ink}", typography: "{typography.caption-uppercase}", rounded: "{rounded.full}", padding: 4px 12px }
  cta-band-dark: { backgroundColor: "{colors.canvas}", textColor: "{colors.ink}", typography: "{typography.display-lg}", padding: 96px }
  newsletter-input-band: { backgroundColor: "{colors.canvas-elevated}", textColor: "{colors.ink}", typography: "{typography.body-md}", rounded: "{rounded.sm}", padding: 32px }
  footer-dark: { backgroundColor: "{colors.canvas}", textColor: "{colors.body}", typography: "{typography.body-sm}", padding: 64px 48px }
  footer-link: { backgroundColor: transparent, textColor: "{colors.body}", typography: "{typography.body-sm}" }

## Overview

Ferrari's marketing site reads as cinematic editorial — closer to a luxury-magazine spread than a typical car-OEM site. The base canvas is near-black ({colors.canvas} — #181818) holding pure white display type; white-canvas bands appear only inside specific editorial contexts (preowned listings, pricing tables, dealer surfaces). The single brand voltage is Rosso Corsa ({colors.primary} — #da291c), the iconic Ferrari racing red, used scarcely on primary CTAs, the Cavallino mark, and Formula 1 race-position highlights.

Type runs FerrariSans as the single sans family at modest weights — display 500, body 400. CTA labels render in uppercase with generous tracking (1.1-1.4px). The brand never uses bold display copy.

The brand's strongest visual signature is the full-bleed cinematic hero photograph — top-of-page imagery shows car photography, model details, or trackside livery without any chrome competing with it. Headlines float over the bottom of the photo or sit in a tight band beneath. Spacing follows the explicit 8px token ladder: xxxs 4 / xxs 8 / xs 16 / sm 24 / md 32 / lg 48 / xl 64 / xxl 96 / super 128.

### Key Characteristics

- Single accent: {colors.primary} (Rosso Corsa #da291c) for primary CTAs, the Cavallino, F1 race-position highlights. Used scarcely.
- Near-black canvas (#181818) — never pure black. White-canvas bands only inside editorial contexts.
- Single sans family: FerrariSans across every text role.
- Display weight stays at 500 — never bold.
- CTA labels render uppercase with 1.4px tracking.
- Sharp {rounded.none} (0px) corners on every CTA, card, and band — luxury-automotive precision.
- Full-bleed cinematic hero photography is the page chrome.
- Explicit 8px spacing token ladder with named scale (xxxs through super).
- Hairlines + photographic depth — no drop shadow tiers.

## Colors

### Brand & Accent
- Rosso Corsa ({colors.primary} — #da291c): The iconic Ferrari racing red. Primary CTA fill, Cavallino mark, F1 driver-position highlights. Used scarcely.
- Rosso Corsa Active ({colors.primary-active} — #b01e0a): Press state.
- Rosso Corsa Hover-darker ({colors.primary-hover} — #9d2211): Documented for completeness; per the no-hover policy this is not used in preview HTML.
- Hypersail Yellow ({colors.accent-yellow-hypersail} — #fff200) + Yellow ({colors.accent-yellow} — #f6e500): Sub-brand accents reserved for the Hypersail sailing program and the global focus-ring color. Not part of the main automotive palette.

### Surface
- Canvas ({colors.canvas} — #181818): Near-black page floor — never pure black, slight warmth.
- Canvas Elevated ({colors.canvas-elevated} — #303030): Cards and panels on dark canvas.
- Canvas Light ({colors.canvas-light} — #ffffff): White editorial bands (preowned listings, pricing).
- Surface Card ({colors.surface-card} — #303030): Same as canvas-elevated — driver cards, livery photo plates.
- Surface Soft Light ({colors.surface-soft-light} — #f7f7f7): Light editorial alternating band.
- Surface Strong Light ({colors.surface-strong-light} — #ebebeb): Light-canvas dividers, badges.

### Hairlines
- Hairline ({colors.hairline} — #303030): 1px divider on dark — same hex as {colors.canvas-elevated}.
- Hairline On Light ({colors.hairline-on-light} — #d2d2d2): 1px divider on light bands.
- Hairline Soft ({colors.hairline-soft} — #ebebeb): Lighter divider.

### Text
- Ink ({colors.ink} — #ffffff): Display, body emphasis on dark.
- Body ({colors.body} — #969696): Default running-text on dark.
- Body Strong ({colors.body-strong} — #ffffff): Same as ink.
- Body On Light ({colors.body-on-light} — #181818): Default text on light bands.
- Muted ({colors.muted} — #666666): Sub-titles, captions on dark.
- Muted Soft ({colors.muted-soft} — #8f8f8f): Disabled link text.
- On Primary ({colors.on-primary} — #ffffff): White text on Rosso Corsa.

### Semantic
- Info ({colors.semantic-info} — #4c98b9): Info badges, callout backgrounds.
- Success ({colors.semantic-success} — #03904a): Confirmation.
- Warning ({colors.semantic-warning} — #f13a2c): Validation warnings.

## Typography

### Font Family
FerrariSans is the licensed single sans family across every text role. Fallback: -apple-system, system-ui, sans-serif. No display/body family split.

### Hierarchy
| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| {typography.display-mega} | 80px | 500 | 1.05 | -1.6px | Homepage hero h1 |
| {typography.display-xl} | 56px | 500 | 1.1 | -1.12px | Subsidiary heroes |
| {typography.display-lg} | 36px | 500 | 1.2 | -0.36px | Section heads, livery band |
| {typography.display-md} | 26px | 500 | 1.5 | 0.195px | Sub-section heads |
| {typography.title-md} | 18px | 700 | 1.2 | 0 | Component titles |
| {typography.title-sm} | 16px | 500 | 1.4 | 0.08px | List labels |
| {typography.body-md} | 14px | 400 | 1.5 | 0 | Default body |
| {typography.body-sm} | 13px | 400 | 1.5 | 0 | Footer body |
| {typography.caption} | 12px | 400 | 1.4 | 0 | Photo captions |
| {typography.caption-uppercase} | 11px | 600 | 1.4 | 1.1px | Section labels, badges |
| {typography.button} | 14px | 700 | 1.0 | 1.4px (uppercase) | CTA pill labels |
| {typography.nav-link} | 13px | 600 | 1.4 | 0.65px (uppercase) | Top-nav menu items |
| {typography.number-display} | 80px | 700 | 1.0 | -1.6px | Race position highlights, spec values |

### Principles
- Display weight stays at 500. Editorial confidence, not bombastic. The cinematic photography is doing the visual heavy-lifting — type doesn't need to compete.
- CTA labels are uppercase with 1.4px tracking. Luxury-precision feel.
- Nav labels are uppercase with 0.65px tracking. Consistent with CTA voice.
- Negative letter-spacing on display only. -0.36px to -1.6px on display sizes; body stays at 0.

### Note on Font Substitutes
FerrariSans is licensed. Open-source substitute: Inter at weight 500 with letter-spacing -1%, or Söhne for closer humanist proportions.

## Layout

### Spacing System
- Base unit: 4px.
- Tokens: {spacing.xxxs} 4px · {spacing.xxs} 8px · {spacing.xs} 16px · {spacing.sm} 24px · {spacing.md} 32px · {spacing.lg} 48px · {spacing.xl} 64px · {spacing.xxl} 96px · {spacing.super} 128px.
- Section padding: {spacing.xxl} (96px) for major bands; {spacing.super} (128px) reserved for hero band depth.

### Grid & Container
- Max content width: ~1280px on editorial bands. Hero photography goes full-bleed.
- Editorial body: 12-column grid.
- Feature card grids: 2-up at desktop for hero splits, 3-up for benefit grids, 4-up for preowned listing tiles.
- Footer: 5-column at desktop.

### Whitespace Philosophy
Generous editorial pacing. Cinematic hero photography occupies generous viewport real-estate; body sections sit in tighter editorial layouts beneath. The canvas-light editorial bands (preowned, pricing) carry tighter density than the dark cinema bands.

## Elevation & Depth

The system uses photographic depth + brightness-step elevation. No drop shadows except a single soft-small {shadow.small} documented in extracted tokens.

| Level | Treatment | Use |
|---|---|---|
| Flat (canvas) | {colors.canvas} (#181818) | Body bands, footer |
| Card | {colors.canvas-elevated} (#303030) | Driver cards, livery plates |
| Light band | {colors.canvas-light} (#ffffff) | Preowned listings, pricing |
| Hairline border | 1px {colors.hairline} or {colors.hairline-on-light} | Card outlines, dividers |
| Soft drop | 0 4px 8px rgba(0,0,0,0.1) | Hovered cards (single shadow tier) |
| Photographic | Full-bleed cinema imagery | Hero band, livery photographs |

### Decorative Depth
- Full-bleed cinema photography is the brand's primary depth treatment.
- Brand red gradient (linear-gradient(180deg, #a00c01, #da291c 64%)): The Rosso Corsa gradient used inside accent bands and CTA hover states.
- Dark grey gradient (linear-gradient(180deg, #3c3c3c, #030303 64%)): Atmospheric darken used at section transitions.
