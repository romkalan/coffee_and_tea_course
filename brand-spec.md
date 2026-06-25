# Brand Spec — Coffee & Tea Mastery Course

Extracted from the Technical Specification (ТЗ).

## Color Tokens

```css
--bg:        #1a120e;    /* Deep dark brown — page canvas */
--surface:   #2a1f18;    /* Lifted surface — cards, containers */
--fg:        #f5f0eb;    /* Warm white — primary text */
--fg-2:      #c68e7a;    /* Terracotta/caramel — secondary text */
--muted:     #a0856e;    /* Warm muted — captions */
--border:    rgba(212, 165, 116, 0.2); /* Semi-transparent accent for dividers */
--accent:    #d4a574;    /* Golden caramel — accent, CTAs, highlights */
--success:   #5a8f5a;    /* Muted green — positive indicators */
```

## Typography

| Role | Font | Weight |
|------|------|--------|
| Display (headings) | Cormorant, Georgia, serif | 600–700 |
| Body | DM Sans, system-ui, sans-serif | 400–500 |
| Monospace | DM Mono, ui-monospace, monospace | 400 |

- Display face: Cormorant (elegant serif) — all headings use `var(--font-display)`
- Body face: DM Sans (modern grotesk) — all body text uses `var(--font-body)`
- No more than 2 families across the entire course

## Visual Voice

- Dark, warm, tactile — coffeehouse atmosphere
- Golden-caramel accent used sparingly for emphasis
- Every module gets a unique color accent (accent variant) for card indicators
- Photography: warm color grading, matte finish
- Icons: outlined, monochrome (accent or white)
- Borders: thin, semi-transparent gold
- No purple gradients, no emoji icons, no generic stock illustrations
