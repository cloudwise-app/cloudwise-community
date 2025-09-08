# CloudWise Brand Assets

This directory contains the canonical visual identity assets for CloudWise.

## Files
- `logo-mark.svg` – Primary logomark with gradient + bars (analytics symbolism).
- `logo-wordmark.svg` – Horizontal lockup (gradient "Cloud" + solid "Wise").
- `logo-monochrome.svg` – Single-color version for emboss, print, low-color contexts.
- `logo-outline.svg` – Outline style for overlays / watermark usage.
- `favicon.svg` – Default favicon (light preference).
- `favicon-dark.svg` – Dark mode favicon (served via media query).

## Usage Guidelines
- Clearspace: At least the height of the tallest bar around all sides.
- Minimum sizes: Favicon 16px; logomark 24px UI; wordmark 120px width.
- Avoid applying additional drop shadows to SVG source; use container shadow tokens instead.
- Never recolor gradient stops independently; treat gradient as brand token.
- Do not rotate, skew, or outline the gradient-filled mark.

## Color Tokens (Reference)
Gradient stops (light mode):
```
#3B82F6 → #2563EB → #059669
```
Dark mode variant:
```
#60A5FA → #3B82F6 → #10B981
```

## Accessibility
- Use monochrome or outline version on complex or photographic backgrounds.
- Maintain contrast ratio ≥ 4.5:1 for adjacent text or supply contrasting container.

## Community Usage
These assets are available for:
- Community discussions and content
- Educational presentations about CloudWise
- Blog posts and articles featuring CloudWise
- Open source projects integrating with CloudWise

## Questions?
For brand usage questions: brand@cloudcostwise.io

## Roadmap
- Add PNG fallbacks (16/32/128) if required by legacy platforms.
- Dynamic OG image generation via server route.
