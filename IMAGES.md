# Demo header images

Every image below is used as `featured-image.jpg` in a page bundle, so the theme
picks it up automatically as that page's header (and, for child pages, as the
Bootstrap card thumbnail).

All photos come from [Pexels](https://www.pexels.com/license/): free for
commercial use, modification allowed, **no attribution required** (credit is
listed here anyway), no reselling the unmodified photo as stock.

| Page bundle | Locale | Subject | Source |
|---|---|---|---|
| `content/en/` (home) | EN | Cape and lighthouse at dusk | [Pexels 39395209](https://www.pexels.com/photo/dramatic-sunset-over-cape-with-lighthouse-view-39395209/) |
| `content/fr/` (home) | FR | Seafront terrace at sunset | [Pexels 19084160](https://www.pexels.com/photo/deckchairs-on-terrace-with-view-of-seashore-19084160/) |
| `content/en/features/` | EN | Aerial shot of a turquoise beach | [Pexels 11670749](https://www.pexels.com/photo/aerial-view-of-beautiful-beach-with-turquoise-water-11670749/) |
| `content/fr/features/` | FR | Open balcony facing the sea | [Pexels 24246924](https://www.pexels.com/photo/view-of-the-sea-from-a-house-terrace-24246924/) |
| `content/en/features/responsive-osm-map/` | EN | Atlantic cliffs at sunrise | [Pexels 35822468](https://www.pexels.com/photo/dramatic-coastal-sunrise-with-cliff-view-35822468/) |
| `content/fr/features/responsive-osm-map/` | FR | Turquoise cove from above | [Pexels 20244788](https://www.pexels.com/photo/aerial-view-of-turquoise-water-beach-and-green-forest-20244788/) |
| `content/fr/features/responsive-google-maps/` | FR | Rock in the sea at sunset | [Pexels 19746165](https://www.pexels.com/photo/cliff-on-seashore-at-dusk-19746165/) |
| `content/en/landing-page/` | EN | Shallow lagoon and reefs | [Pexels 8521879](https://www.pexels.com/photo/aerial-view-of-a-bay-with-turquoise-water-8521879/) |
| `content/fr/landing-page/` | FR | Sailboat on a calm sea | [Pexels 11054722](https://www.pexels.com/photo/boat-in-the-middle-of-the-blue-sea-11054722/) |

## Still on the theme default header

- `features/default-header` (both locales) — kept without `featured-image.jpg` on
  purpose: the page documents the `static/img/header-960.jpg` fallback.
- `features/gallery-page-type` (both locales) — left alone: the gallery partials
  render every image resource of the bundle, so a `featured-image.jpg` would end
  up inside the gallery itself.
