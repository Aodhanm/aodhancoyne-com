# aodhancoyne.com

Personal site: projects, published datasets, and writing on early California history.

Static HTML, no build step, no external requests, no tracking. Served by GitHub Pages
at the apex domain `aodhancoyne.com` (see `CNAME`).

## Layout

`index.html` is the whole site. It is set as a broadside: a masthead, a lede band, then
three CSS columns of articles, each with its own cut (image) and caption.

Assets in `assets/` all come from the projects themselves:

| File | What it is |
|---|---|
| `ms-croix.jpg` | Savage transcript leaf: bando of Teodoro de Croix, Chihuahua, 22 March 1778. C-A 1 |
| `ranchos-map.jpg` | The ranchos register mapped, coloured by governor |
| `brands.jpg` | Six registered cattle brands, 1822–1859 |
| `maps-moraga.jpg` | Gabriel Moraga's expeditions, 1806–1817 |
| `ships-traffic.jpg` | Vessel traffic by flag, 1769–1846, from the ship registry |
| `alcalde-brand.jpg` | Alcalde Books crest and wordmark |

## Editing

Adding an article: copy an `<div class="art">` block. Cuts take one of
`tall` / `wide` / `pad` / `lockup`, plus `mono` to print black and white.

## Games

Games are deliberately not listed. Two quiet ways through to
`games.aodhancoyne.com`: the ornament (❧) at the foot of the colophon, and typing
`kedr` anywhere on the page.

## Figures

Counts in the articles were read from the live sites on 2026-09-11. They are static and
need updating by hand when a project's numbers move.

## Known, still to do

- The masthead falls back to Iowan Old Style because Playbill/Bodoni are not reliably
  installed. Needs either a self-hosted display face or an inline-SVG wordmark.
- Column balance is left to CSS flow; long articles can break awkwardly at some widths.
- "Vol. I · No. 1" implies an issue schedule. Decide whether to keep it.
- The lede paragraph is placeholder prose and should be replaced.
