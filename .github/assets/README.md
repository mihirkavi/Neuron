# README images

Images used by the root [README](../../README.md) of Neuron. They are presentation assets only; the app does not load them.

## Files

| File | What it is |
| --- | --- |
| `banner-light.png`, `banner-dark.png` | Title banner for light and dark GitHub themes, rendered from [`source/banner.html`](source/banner.html) with headless Chromium |
| `hero.jpg` | Framed desktop and phone screenshot used at the top of the README |
| `screenshots/problem.jpg`, `solution.jpg`, `sensors.jpg`, `technology.jpg` | Sections of the concept website: the problem, the device, the sensor array and the planned platform |

## Visual identity

Neuron's README uses a **site blueprint** look: an engineering-style site plan with one sensor node, its coverage rings and sensor callouts, plus a drawing title block that says "Concept".

- **Fonts:** Archivo (expanded, extra bold) for headlines, IBM Plex Mono for drawing labels and tags, Inter for body text, matching the concept website.
- **Colors:** indigo `#6366f1` and emerald `#10b981` from the logo and the site's `:root` variables, ink `#111827`, blueprint paper `#f5f6fb`; the dark banner uses navy `#0e1324` with indigo `#818cf8` and emerald `#34d399`.
- **Badges** use `10b981`, `4f46e5`, `1f2937` and `6b7280`. Section labels use small monospace codes instead of emoji.
- **Re-render:** see [`source/README.md`](source/README.md).

## How they were made

Captured on 2026-10-26 from the live concept website (https://mihirkavi.github.io/Neuron/) with headless Chromium at 1440 × 900 (desktop) and 390 × 844 (phone). Screenshots are framed in a browser window or phone outline by a small Playwright script, then saved as JPEG.

## Notes for agents

- Screenshots must show only public pages or demo data, never personal, financial or health information.
- Keep names lowercase with hyphens. When you replace an image, keep its file name so README links keep working, and update this table.
- Retake screenshots after visible interface changes so the README stays truthful.
