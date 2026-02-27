# Solarium — Promotional Website

Single-page promotional site for **Solarium**, a post-apocalyptic visual novel.

## Local development

Serve from the **project root** (one level up, where `game/` and `site/` live) so asset paths resolve correctly:

```bash
python3 -m http.server 3456
```

Then open [http://localhost:3456/site/](http://localhost:3456/site/)

## Assets

All game images are referenced via `/game/images/…` and must be present in the parent directory.  
Place the trailer at `/site/trailer.mp4` (not committed — too large for git).

## Tech

- Vanilla HTML / CSS / JS — no build step  
- Fonts: Cormorant Garamond + Inter (Google Fonts)  
- Parallax, IntersectionObserver reveals, mobile hamburger nav
