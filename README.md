# Horizons planting guide assets

Static hosting for the native planting guides used by the Manawatū-Whanganui
native planting map. Served via GitHub Pages from `docs/`.

Everything here is linked from popups in an ArcGIS Online web map and from the
accompanying story map. Nothing in this repo runs — it's images, PDFs and embed
HTML.

## What's here

| | |
|---|---|
| `docs/*.jpg` | 26 guide pages, 1400 px wide, ~290 KB each. Used as popup images. |
| `docs/*.pdf` | 24 planting guides at full quality, for download. |

Guides cover 38 potential ecosystem types across the region. Several types share
a guide — the beech forests all point at `CLF10_CLF11_CLF12_planting_guide`, for
example — so there are fewer files than ecosystem types.

## Linking to a guide

Files are named after the ecosystem codes they cover, with spaces and ampersands
replaced so the URLs need no escaping:

```
https://ctregurtha-nairn.github.io/horizons-planting-guides/WF8_planting_guide_p1.jpg
https://ctregurtha-nairn.github.io/horizons-planting-guides/WF8_planting_guide.pdf
```

Image files carry a `_p1`, `_p2` … page suffix. Most guides are a single page;
the dune guide has four (an introduction, then front, middle and rear dune).

## About the mapping

The map behind these guides uses the Singers & Rogers potential ecosystem
classification. That describes what would grow at a site given its climate,
soils and landform, in the absence of human clearance — **not** what grows there
now.

It's regional-scale modelling rather than a site survey. A property may straddle
two mapped types, and local conditions such as drainage, exposure, frost or
altered hydrology strongly affect what actually survives. The guides are a
well-informed starting point, not a planting plan.

Coastal sites need particular care — dune systems are specialised, and the dune
guide should be read alongside the Coastal Restoration Trust's guidance.

## Credits

Ecosystem classification after Singers & Rogers (2014), *A classification of New
Zealand's terrestrial ecosystems*. Potential ecosystem mapping and planting
guides by Horizons Regional Council.
