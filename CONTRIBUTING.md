# Contributing

Thanks for helping keep the GDG Sri Lanka brand assets accurate and complete! 🎉

## What you can contribute

- **New communities or events** — add a folder for a new GDG chapter, program, or event.
- **New formats** — vector (`.svg`) or print (`.pdf`) versions of existing logos.
- **New variants** — a missing `white` (dark-background) or `icon` version.
- **Fixes** — replacing an outdated or low-resolution logo.

## Folder & naming convention

Place each community's assets in its own folder under [`logos/`](logos):

```
logos/<community-slug>/<community-slug>-<layout>-<color>.<ext>
```

- **community-slug** — lowercase, hyphenated (e.g. `gdg-cloud-sri-lanka`).
- **layout** — `horizontal`, `stacked`, or `icon`.
- **color** — `color` (light backgrounds) or `white` (dark backgrounds).
- **ext** — `png` preferred; add `svg` for scalable vectors when available.

Examples:

```
logos/gdg-sri-lanka/gdg-sri-lanka-horizontal-color.png
logos/gdg-sri-lanka/gdg-sri-lanka-icon-white.png
```

### Banners and graphic elements

Event artwork lives in its own top-level folders:

```
banners/<event-slug>/<event-slug>-<purpose>-<width>x<height>.png
elements/<kit-slug>/<style>/<kit-slug>-<style>-<name>.<ext>
```

Examples:

```
banners/devfest-sri-lanka-2026/devfest-sri-lanka-2026-x-header-1500x500.png
elements/devfest-2026/filled/devfest-2026-filled-arrow.svg
```

Export banners at the platform's full pixel size (banners may have solid backgrounds).
Ship elements as SVG, plus a transparent PNG.

## Asset requirements

- **Transparent background** (PNG/SVG) — no baked-in white or colored backgrounds.
- **High resolution** — at least ~2000px on the longest edge for raster; prefer SVG.
- Trimmed padding, but keep the logo's own internal clear space.

## How to submit

1. Fork this repository and create a branch.
2. Add your files following the convention above.
3. Add a preview + link in [`README.md`](README.md) and the relevant folder `README.md`.
4. Open a pull request describing what you added or changed.

Please make sure you have the right to share any asset you contribute, and that it follows
the [trademark terms](TRADEMARKS.md).
