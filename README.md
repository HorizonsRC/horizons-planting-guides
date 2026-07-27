# Horizons planting guide assets

Static hosting for the native planting guides used by the Manawatū-Whanganui
Native Planting Guide. Served via GitHub Pages from `docs/`.

Everything here is linked from popups in an ArcGIS Online web map and from the
accompanying story map. Nothing in this repo runs. It is images and PDFs only.

## What's here

| | |
|---|---|
| `docs/*.jpg` | 26 guide pages, 1400 px wide, around 290 KB each. Used as popup images. |
| `docs/*.pdf` | 24 files: 23 planting guides at full quality for download, plus `Introduction_pages.pdf`. |

Guides cover 38 potential ecosystem types across the region. Several types share
a guide. The beech forests all point at `CLF10_CLF11_CLF12_planting_guide`, for
example, so there are fewer files than ecosystem types.

## Linking to a guide

Files are named after the ecosystem codes they cover, with spaces and ampersands
replaced so the URLs need no escaping:

```
https://horizonsrc.github.io/horizons-planting-guides/WF8_planting_guide_p1.jpg
https://horizonsrc.github.io/horizons-planting-guides/WF8_planting_guide.pdf
```

Image files carry a `_p1`, `_p2` and so on page suffix. Most guides are a single
page; the dune guide has four (an introduction, then front, middle and rear
dune).

These addresses are stored in full on every feature of the hosted layer, in the
`Guide_IMG`, `Guide_PDF`, `Guide2_IMG` and `Guide2_PDF` fields. Renaming a file
or moving this repo breaks every popup until those fields are rewritten.

## Related ArcGIS Online items

| Item | Name |
|---|---|
| Hosted feature layer | `HRC_Planting_Guide_Ecosystems` |
| Instant App | `HRC Planting Guide Zone Lookup` |
| Story map | Manawatū-Whanganui Native Planting Guide |

## About the mapping

The map behind these guides uses the Singers & Rogers potential ecosystem
classification. That describes what would grow at a site given its climate,
soils and landform, in the absence of human clearance. It is **not** what grows
there now.

It's regional-scale modelling rather than a site survey. A property may straddle
two mapped types, and local conditions such as drainage, exposure, frost or
altered hydrology strongly affect what actually survives. The guides are a
well-informed starting point, not a planting plan.

Coastal sites need particular care. Dune systems are specialised, and the dune
guide should be read alongside the Coastal Restoration Trust's guidance.

## Credits

Ecosystem classification after Singers & Rogers (2014), *A classification of New
Zealand's terrestrial ecosystems*. Potential ecosystem mapping and planting
guides by Horizons Regional Council.
