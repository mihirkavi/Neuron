# Banner source

`banner.html` is the self-contained source of `../banner-light.png` and `../banner-dark.png`. It uses Google Fonts and an inline SVG drawing, and switches palettes with `prefers-color-scheme`.

## Re-render

With Playwright's Chromium available, render at 1600 × 600 and 2× scale, once per color scheme (the README kit's `render-html.mjs` does this):

```bash
node render-html.mjs .github/assets/source/banner.html .github/assets/banner-light.png --scheme light
node render-html.mjs .github/assets/source/banner.html .github/assets/banner-dark.png --scheme dark
```

## Notes for agents

- Keep the "Concept · not built" tag and the "illustrative" label on the site plan: the drawing shows a proposed device, not a deployment.
- Colors and fonts are documented in [`../README.md`](../README.md). Check both PNGs for overflow after any edit.
