# Demo header and gallery images

Photos used by the demo content. All of them come from
[Pexels](https://www.pexels.com/license/): free for commercial use, modification
allowed, **no attribution required** (credit is listed here anyway), no reselling
the unmodified photo as stock.

## Page headers (`featured-image.jpg` in a page bundle)

The theme picks it up automatically as that page's header (and, for child pages,
as the Bootstrap card thumbnail).

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
| `content/en/features/gallery-page-type/` | EN | Lighthouse silhouette at dusk | [Pexels 22699910](https://www.pexels.com/photo/silhouette-of-island-with-building-and-lighthouse-on-evening-22699910/) |
| `content/fr/features/gallery-page-type/` | FR | Wide beach and dunes | [Pexels 6793005](https://www.pexels.com/photo/beach-dunes-6793005/) |
| `content/fr/features/shortcode-gallery/` | FR | Lighthouse in black and white | [Pexels 13029244](https://www.pexels.com/photo/grayscale-photo-of-a-lighthouse-in-cape-elizabeth-maine-13029244/) |

## Gallery photos

The demo galleries are page bundles, and Hugo serves the bundle images to both
language mounts (`ByType "image"` returns the whole set; only a same-named
`featured-image.jpg` is language-specific). These photos therefore show up in
both the EN and the FR gallery, which is what makes the FR galleries non-empty.

| Bundle | File | Subject | Source |
|---|---|---|---|
| `content/fr/features/gallery-page-type/` | `plage-aerienne.jpg` | Aerial view of a turquoise beach | [Pexels 31958539](https://www.pexels.com/photo/aerial-view-of-sunny-florida-beach-with-turquoise-waves-31958539/) |
| `content/fr/features/gallery-page-type/` | `balcon-mer.jpg` | Terrace above the sea | [Pexels 31405933](https://www.pexels.com/photo/seaside-terrace-with-ocean-view-31405933/) |
| `content/fr/features/gallery-page-type/` | `phare-lande.jpg` | Lighthouse under an overcast sky | [Pexels 19624754](https://www.pexels.com/photo/lighthouse-against-a-clouded-sky-at-dusk-19624754/) |
| `content/fr/features/shortcode-gallery/` | `crique-rocheuse.jpg` | Rocky shore and turquoise water | [Pexels 25430526](https://www.pexels.com/photo/turquoise-water-on-ocean-shore-with-sandy-beach-25430526/) |
| `content/fr/features/shortcode-gallery/` | `coquelicots.jpg` | Field of red poppies | [Pexels 11522725](https://www.pexels.com/photo/red-poppy-flowers-in-the-field-11522725/) |
| `content/fr/features/shortcode-gallery/` | `champ-dore.jpg` | Wheat field with a lone poppy | [Pexels 4490065](https://www.pexels.com/photo/agricultural-field-with-tractor-trace-in-countryside-4490065/) |
| `content/fr/features/shortcode-gallery/` | `bois-echoue.jpg` | Driftwood on a beach | [Pexels 12182292](https://www.pexels.com/photo/sand-dunes-on-sea-beach-12182292/) |

## Still on the theme default header

`features/default-header` (both locales) is kept without a `featured-image.jpg`
on purpose: the page documents the fallback, which comes from the theme itself
(`static/img/header-960.jpg`, a misty forest at dawn — Pexels 35664581).
