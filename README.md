# Rush Chicago Weekend — Trip Itinerary

A single-page, visually rich itinerary for a July 2026 trip: Sterling, IL → Chicago, IL, built around seeing **Rush: Fifty Something** at the United Center.

## What's inside

- Day-by-day itinerary (Friday Sterling → Saturday Chicago/Rush → Sunday wrap-up)
- Linked restaurants, hotel, and venue for quick reference
- An "Explore More" section with an embedded map and categorized index of nearby attractions, restaurants, and points of interest

## Deploy

This is a single static `index.html` with no build step and no dependencies.

**Vercel:**
1. Import this repo at [vercel.com/new](https://vercel.com/new)
2. Framework preset: **Other** (no build command needed)
3. Deploy — that's it

**Anywhere else:** any static host (GitHub Pages, Netlify, Cloudflare Pages) will work the same way — just point it at `index.html`.

## Editing

Everything lives in `index.html` — HTML, CSS, and JS are all inline in the one file. Open it in any editor and search for the section you want to change (day sections are commented, e.g. `<!-- ============ DAY 1 ============ -->`).
