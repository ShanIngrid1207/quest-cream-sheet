# Quest Drafting — "Cream Sheet" design direction

An alternate design direction for **Quest Drafting & Design LLC**, Gilbert, Arizona.

**Live preview:** https://shaningrid1207.github.io/quest-cream-sheet/

## What this is

A standalone, single-file design exploration — not the live site. The production
site is a separate Astro build. This page exists to look at and react to.

It was driven by three reference designs, each mapped onto the section it fits best:

| Reference | Used for |
|---|---|
| Mindpalace dashboard | Hero — framed window, side rails, question cards |
| Superdry brand-language card | Services — spec-sheet boxes, size chips, peach panel |
| Scentora checkout | Work — thin-rule project table, order-summary panel |

## Colors

Every value is taken from the live site's stylesheet, with the dominance inverted —
cream page instead of graphite page.

| Role | Value |
|---|---|
| Page | `#EAE7E1` |
| Raised panel | `#F7F5F1` |
| Ink | `#16181A` |
| Muted | `#63605B` |
| Accent (logo orange) | `#E8552B` |
| Accent, small text | `#B23D18` |
| Peach fill | `#F7DBCD` — the orange tinted into the cream |
| Dark surfaces | `#191B1D` |

Typefaces are unchanged from the live site: Anton, Archivo, JetBrains Mono, Caveat.

## Running it

No build step. Open `index.html` directly, or serve the folder:

```bash
python -m http.server 8000
```

## Notes

- All copy and photography come from the production site — no placeholder text,
  no stock imagery.
- The page is marked `noindex` so it can't compete with the real site in search.
- Verified at 1440px and 390px.
