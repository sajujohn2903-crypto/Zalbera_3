# Zalbera · Maison de Parfum

Black-and-gold landing page for Zalbera eau de parfum: a slowly spinning 3D gold bottle behind the
title, gold dust, a notes marquee, the Maison manifesto, a horizontal-scroll collection of all
8 fragrances, the Alfaro signature section with interactive notes, a "find your scent" mood picker,
the craft pillars, an email sign-up and footer.

## Files
- `index.html`: the page (layout, styles, animations)
- `hero3d.js`: the 3D bottle in the hero (three.js and the model, bundled into one file)
- `img/`: product photos; `assets/`: Zalbera logo mark and wordmark (SVG)
- Fonts: Marcellus and Tenor Sans from Google Fonts. Smooth scrolling: Lenis from jsDelivr.

## Run locally
`hero3d.js` is a JavaScript module, so serve the folder instead of double-clicking `index.html`:

```
python3 -m http.server 8000
```

then open http://localhost:8000. It can be hosted as-is on GitHub Pages.

## Not connected yet
"Add to bag" and the email sign-up only work on the page; they are not connected to a store or a
mailing list.
