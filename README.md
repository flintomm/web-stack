# web-stack

**A field manual to the modern web stack** &mdash; build, source, hosting, backend, insight.
14 tools across 5 layers, every price verified, every relationship drawn.

## Pages

- [`index.html`](./index.html) &mdash; The diagram
- [`hardware.html`](./hardware.html) &mdash; Cloud = rented hardware (Rosetta layer)
- [`flow.html`](./flow.html) &mdash; How it links together (wiring diagram)
- [`audit.html`](./audit.html) &mdash; The audit (cost, overlaps, gaps)
- [`about.html`](./about.html) &mdash; About this map

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

This repo is designed for GitHub Pages. After pushing:

1. Repo &rarr; Settings &rarr; Pages
2. Source: **Deploy from a branch**
3. Branch: `main`, folder: `/ (root)`
4. Wait ~30 seconds, then visit `https://flintomm.github.io/web-stack/`

The `.nojekyll` file disables Jekyll processing so file paths just work.

## License

Code: MIT. Content: CC0.

REV. 2026.05
