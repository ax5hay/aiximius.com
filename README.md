<div align="center">

# aiximius.com

**The Aiximius company site: a hand-built static landing page.**

[![Live](https://img.shields.io/badge/live-www.aiximius.com-0b0b0f?style=for-the-badge&logoColor=white)](http://www.aiximius.com)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github&logoColor=white)

</div>

---

A single-page marketing site, written by hand (no framework, no build step) and served straight
from **GitHub Pages** on the apex domain via `CNAME`. Fast because there is nothing to hydrate.

## What ships here

| Piece | File(s) |
|-------|---------|
| The page | `index.html`: all markup, styles, and copy |
| Brand & hero art | `logo header.png`, `hero-bg.png`, `final low res.png`, product hero SVGs |
| Case-study imagery | `case study *.jpeg` (Merakiel, Dixit, Rude, and others) |
| Domain binding | `CNAME` → `aiximius.com` |
| Discoverability | `sitemap.xml`, `robots.txt`, `og image.png` for link previews |

## Deploy

Push to the default branch: GitHub Pages serves the root. The `CNAME` file keeps the custom
domain mapped. To preview locally:

```bash
python3 -m http.server 8000  # then open http://localhost:8000
```
