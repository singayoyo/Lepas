# LEPAS Working Design Guide

Status: working design guide for this local LEPAS experience, not an official LEPAS brand book.
Last updated: 2026-09-11.

## Evidence Base

This guide combines:

- The current local hero composition in `lepas-home.html` and `assets/lepas-hero-panorama.png`.
- Official LEPAS public pages for Brand Story and Brand Values.
- Chery/LEPAS launch material and current public design-language coverage.

No public downloadable LEPAS brand manual, official colour table, or official typography specification was found during this pass. Treat exact hex values below as extracted working tokens for this project.

## Brand Summary

LEPAS is positioned around elegant mobility, lifestyle expression, and a design-led SUV identity. The name is described by LEPAS as a fusion of "LEAP" and "PASSION", carrying agility, vitality, elegance, and passion.

The public brand language consistently centres on:

- Elegant mobility.
- Leopard Aesthetics.
- Speed, power, and elegance.
- Warm technology, not cold specification.
- Urban elites and lifestyle explorers.
- Design as self-expression.

Recommended local brand line:

> Bold mobility, elegant control, expressive technology.

## Colour System

### Core Neutrals

Use these for the page chrome, navigation, text, and calm whitespace.

| Token | Hex | Use |
| --- | --- | --- |
| `--lepas-ink` | `#171B22` | Primary text, navigation, logo-adjacent UI |
| `--lepas-black` | `#101010` | Maximum contrast, deep grille/tyre references |
| `--lepas-charcoal` | `#2B3846` | Dark panels, technical details, chart axes |
| `--lepas-slate` | `#485A58` | Secondary UI, muted labels |
| `--lepas-line` | `#EEF0F2` | Header rule, light dividers |
| `--lepas-white` | `#FFFFFF` | Header, negative space |
| `--lepas-mist` | `#F4F2EE` | Warm off-white page background |

### Atmospheric Palette

These come from the sky, road, ocean, and soft photographic conditions in the current hero.

| Token | Hex | Use |
| --- | --- | --- |
| `--lepas-cloud` | `#DBE0E6` | Soft blue-grey backgrounds |
| `--lepas-warm-cloud` | `#DBD5CE` | Warm neutral panels |
| `--lepas-silver` | `#C3C7C8` | Subtle surfaces, subdued chart fills |
| `--lepas-ocean-haze` | `#BFC0C3` | Secondary background bands |
| `--lepas-asphalt` | `#897E7B` | Grounded muted copy, footer surfaces |
| `--lepas-stone` | `#AFA297` | Warm neutral contrast |

### Vehicle Accent Palette

These should be used sparingly, as accent moments rather than full-page themes.

| Token | Hex | Use |
| --- | --- | --- |
| `--lepas-deep-teal` | `#183840` | Primary automotive accent, premium dark teal |
| `--lepas-teal` | `#306078` | Data highlight, buttons, active states |
| `--lepas-teal-glow` | `#50A870` | Positive status, green model accent |
| `--lepas-forest` | `#286020` | Secondary green accent |
| `--lepas-gold` | `#A0913D` | Heroic product accent, premium signal |
| `--lepas-bronze` | `#705828` | Gold shadow, warm secondary accent |
| `--lepas-headlamp` | `#D2ECFF` | Light effects, glints, focus halo |

### Recommended CSS Variables

```css
:root {
  --lepas-ink: #171B22;
  --lepas-black: #101010;
  --lepas-charcoal: #2B3846;
  --lepas-slate: #485A58;
  --lepas-line: #EEF0F2;
  --lepas-white: #FFFFFF;
  --lepas-mist: #F4F2EE;

  --lepas-cloud: #DBE0E6;
  --lepas-warm-cloud: #DBD5CE;
  --lepas-silver: #C3C7C8;
  --lepas-ocean-haze: #BFC0C3;
  --lepas-asphalt: #897E7B;
  --lepas-stone: #AFA297;

  --lepas-deep-teal: #183840;
  --lepas-teal: #306078;
  --lepas-teal-glow: #50A870;
  --lepas-forest: #286020;
  --lepas-gold: #A0913D;
  --lepas-bronze: #705828;
  --lepas-headlamp: #D2ECFF;
}
```

## Colour Usage Rules

1. Keep the base mostly white, mist, ink, and cloud.
2. Use teal and gold as product energy accents, not as dominant backgrounds.
3. Use charcoal for technical credibility, especially reporting and data modules.
4. Use gold only for premium emphasis, hero accents, and campaign highlights.
5. Use headlamp blue for focus rings, glints, and motion/light language.
6. Avoid generic purple-blue gradients, crypto-style neon green, and heavy black dashboards.

## Typography

No official LEPAS typography specification was found in public sources.

Working recommendation:

- Navigation and UI: `Arial`, `Helvetica Neue`, `Helvetica`, sans-serif.
- Reports and dashboards: keep the existing project pairing of `Montserrat` for headings and `Source Sans 3` for body when the work is data-heavy.
- Logo: use the supplied LEPAS wordmark image or an approved vector. Do not recreate the wordmark in a font.

Type behaviour:

- Use confident, clean, unfussy text.
- Avoid tiny grey enterprise dashboard typography.
- Use direct headings that state a result or category.
- Do not over-explain the UI in visible text.

## Logo Guidance

Public pages show the LEPAS identity as a black script-style wordmark. For this project:

- Use the wordmark on white or very light mist backgrounds.
- Preserve clear space around the logo.
- Do not place the wordmark over busy vehicle photography unless a tested white/reversed logo asset is available.
- Do not redraw, stretch, skew, outline, or add effects to the wordmark.

## Imagery Direction

LEPAS public language is strongly nature and leopard inspired. Use imagery that supports:

- Elegant SUV proportions.
- Strong shoulder lines.
- Distinctive lamp signatures.
- Motion, speed, confidence, and controlled power.
- Refined lifestyle settings rather than rugged off-road cliches.

For local web work:

- Product should be visible in the first viewport.
- Avoid dark, blurred, purely atmospheric vehicle crops.
- Preserve the clean editorial whitespace from the current page.
- Use coastal, city, or premium lifestyle environments when they support "elegant mobility."

## Motion Direction

Motion should feel controlled and premium.

Use:

- Slow reveal.
- Light glints.
- Smooth parallax.
- Subtle hover states.

Avoid:

- Aggressive blinking.
- Gimmicky flashing headlamps.
- Constant dashboard animation.
- Effects that make the vehicle feel toy-like.

## Voice And Copy

Voice should be direct, elegant, and confident.

Use:

- "Drive Your Elegance."
- "Elegant mobility."
- "Leopard Aesthetics."
- "Warm technology."
- "Power with refinement."
- "Design-led mobility."

Avoid:

- Overly technical specification stacking.
- Empty luxury cliches.
- Generic ad-platform language.
- Anything that sounds like a default dashboard template.

## Product And Brand Architecture

Public LEPAS material identifies L8, L6, and L4 as core model lines. A LEPAS news item describes L8 as the elegant flagship, L6 for trendsetting creators, and L4 for younger consumers.

For this local paid-media context, the navigation labels are campaign channels:

- Meta
- TikTok
- Programmatic
- YouTube

Keep that distinction clear: these are media sections, not LEPAS model names.

## UI Direction For This Project

The current `lepas-home.html` should remain:

- White header.
- Black LEPAS wordmark.
- Centered channel navigation.
- Full-width vehicle hero.
- Generous white continuation space.

Future reporting or campaign pages should feel like a LEPAS artefact, not a platform export:

- Start with the verdict.
- Use bold, legible figures.
- Use the vehicle accent palette for meaning.
- Keep evidence below the first impression.
- Make all metrics defensible.

## Accessibility Notes

- Check all text/background pairs against WCAG 2.2 AA before production.
- Do not use colour as the only signal in charts.
- Keep focus rings visible; `--lepas-headlamp` can work as a brand-consistent focus halo when contrast is sufficient.
- Honour reduced motion.
- Keep the page readable at 200% zoom.

## Sources Checked

- LEPAS Brand Story: https://www.lepasinternational.com/aboutlepas/brandstory/index.shtml
- LEPAS Brand Values: https://www.lepasinternational.com/aboutlepas/brandvalues/index.shtml
- LEPAS international news, "Drive Your Elegance": https://www.lepasinternational.com/news/news_qy/detail-95.shtml
- Chery/PRNewswire launch release: https://www.prnewswire.com/il/news-releases/cherys-new-brand---lepas-unveils-first-vehicle-redefining-elegant-mobility-302432943.html
- Chery Malaysia launch article: https://www.chery.my/2025/04/28/a-new-global-brand-redefining-future-mobility-with-elegant-designing/
- Car Design News design-language article: https://www.cardesignnews.com/cars/how-nature-inspired-surfacing-defines-the-lepas-design-language/2700676
