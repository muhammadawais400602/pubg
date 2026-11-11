# Angry Tepes — PUBG Streamer Landing Page

A single-page landing site for the Angry Tepes PUBG stream: hero with the live feed, weekly broadcast schedule, viral highlights, loadout telemetry, stream rig, and the Discord recruitment section.

## Stack

- Static `index.html`, no build step
- Tailwind CSS (Play CDN) with the design tokens set up in the inline `tailwind.config`
- Google Fonts: Oswald, Inter and Material Symbols
- Images live in `assets/img/`

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Any static host works (GitHub Pages, Vercel or Netlify). Serve the repo root.

## To do

The social, Twitch/YouTube/Kick, Discord invite and footer links are placeholders (`#`). Replace them with your real URLs in `index.html`.
