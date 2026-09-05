# Fathom

> Data that flows. Insights that run deep.

Fathom is a data management & analytics startup providing managed technology solutions for:

- **Data Ingestion** — batch & real-time streaming from 100+ source connectors
- **Data Lake Management** — open-format lakehouse storage (Iceberg / Delta / Hudi)
- **Data Pipelines** — observable ELT pipelines with lineage and orchestration
- **Analytics** — semantic metrics layer, BI dashboards, and embedded analytics API

## This repository

Contains the marketing/landing website for Fathom — a self-contained single-page HTML site.

### Structure

```
├── index.html       # Landing page (self-contained, no build step)
├── netlify.toml     # Netlify deployment config
└── README.md        # This file
```

## Deploy

The site is deployed on **Netlify**. It's a static site — no build step required.

To deploy locally:

```bash
# Just open the file
open index.html

# Or serve it
python3 -m http.server 8000
```

## Tech

- Pure HTML/CSS — no JavaScript framework
- Self-contained (fonts loaded from Google Fonts CDN)
- Responsive (mobile, tablet, desktop)
- Light/dark mode via `prefers-color-scheme`
- Respects `prefers-reduced-motion`

## License

© 2026 Fathom Data Technologies. All rights reserved.
