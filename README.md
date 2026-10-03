# ykstorm.github.io

Source for [ykstorm.github.io](https://ykstorm.github.io): case studies of the backend systems I've built, Homesty, Anvil, Anchor, Tripwire and Stackup, each with the problem, the exact mechanism and what shipped.

It's one static page: plain HTML and CSS, two hand-drawn inline SVGs, and a small canvas sketch in the hero that respects reduced motion. There is no build step; GitHub Pages serves `index.html` from `main` as it is.

To preview it locally:

```
python -m http.server 8000
```

then open http://localhost:8000.
