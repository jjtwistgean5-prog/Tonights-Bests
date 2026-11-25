# Tonight's Best Deep-Sky Planner

Ranks galaxies, nebulae and star clusters by how well you can see them tonight from your location, sky darkness and instrument.

## Stack

- One static page: `index.html` (HTML, CSS, vanilla JavaScript)
- No build step, no backend, no database, no environment variables
- Settings are saved in the visitor's own browser (`localStorage`)
- Loads Google Fonts; everything else is in the page

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy on Vercel

Import this repository in Vercel with these settings:

- Framework Preset: **Other**
- Build Command: leave empty
- Output Directory: leave empty (the repository root)
- Install Command: leave empty

`vercel.json` turns on clean URLs and adds basic security headers.
