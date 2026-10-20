# Adelaide Art Walk

Mobile-first bilingual public art walking guide for Adelaide CBD.

## Features

- Leaflet + OpenStreetMap interactive map
- English / Japanese language toggle
- Curated walking routes with polyline overlays
- Artwork detail modal with image, artist, category, and description
- Browser geolocation button
- Five locally stored Adelaide artwork images with attribution notes in `assets/art/ATTRIBUTIONS.md`

## Run locally

Serve the repository root with any static web server, for example:

```bash
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

This prototype uses CDN-hosted Tailwind CSS, Leaflet, Google Fonts, and artwork preview images.
