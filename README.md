# Zalbera · Maison de Parfum

Black-and-gold landing page for Zalbera eau de parfum: a slowly spinning 3D gold bottle behind the
title, gold dust, a notes marquee, the Maison manifesto, a horizontal-scroll collection of all
8 fragrances, the Alfaro signature section with interactive notes, a "find your scent" mood picker,
the craft pillars, an email sign-up and footer.

## Files
- `index.html`: the landing page (layout, styles, animations)
- `product.html`: a page for each of the 8 fragrances, opened by name, e.g. `product.html#alfaro`. Gallery, sizes, Add to bag, Buy now, slide-out bag, notes (top / heart / base), story, reviews and "You may also like"
- `hero3d.js`: the 3D bottle in the hero (three.js and the model, bundled into one file)
- `img/`: product photos (`img/p/` for the product page galleries); `assets/`: Zalbera logo mark and wordmark (SVG)
- Fonts: Marcellus and Tenor Sans from Google Fonts. Smooth scrolling: Lenis from jsDelivr.

## Run locally
`hero3d.js` is a JavaScript module, so serve the folder instead of double-clicking `index.html`:

```
python3 -m http.server 8000
```

then open http://localhost:8000. It can be hosted as-is on GitHub Pages.

## Not connected yet
- Prices are placeholders (AED 250 for 50 ml, AED 395 for 100 ml): edit `SIZES` in `product.html`.
- The bag is kept in the visitor's browser and checkout is not connected to payments.
- Reviews start empty and are saved only in the visitor's browser.
- The email sign-up is not connected to a mailing list.
