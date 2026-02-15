# Local Business Website Production (Shelburne, Ontario)

This repository contains production-ready static website bundles for multiple local businesses.

## Contents
- `bundles/`: deployable static sites (HTML + assets) per business
- `brochures/`: print-ready outreach material (if present)

## How To Preview Locally
From repo root:

```bash
python3 -m http.server 8080
```

Then open:
- `http://localhost:8080/bundles/the-duffy/`
- `http://localhost:8080/bundles/shannon-s-tap-grill/`
- `http://localhost:8080/bundles/happy-dragon-express/`
- `http://localhost:8080/bundles/main-st-cafe/`
- `http://localhost:8080/bundles/pelican-tap-grill/`
- `http://localhost:8080/bundles/curry-mantra/`
- `http://localhost:8080/bundles/mrs-mitchell-s-restaurant/`
- `http://localhost:8080/bundles/reggae-flava-kitchen/`
- `http://localhost:8080/bundles/de-marco-s-caffe-inc/`
- `http://localhost:8080/bundles/reserve-slot-for-additional-business/`

## Deploy
Each folder under `bundles/<site>/` can be deployed as a static site on any host that serves files (Render static site, Netlify, Vercel static output, S3/CloudFront, GitHub Pages, etc.).
