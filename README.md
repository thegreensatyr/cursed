# cursedworlds.com

Static site for the **Cursed Worlds** book series by B. Xen Osiris Zane.

## Deploying
This repo is connected to Netlify. **Push to `main` and it deploys automatically.**
No zips. No drag-and-drop. Every deploy has history and can be rolled back in one click.

## Structure
- `index.html` — main series site
- `read.html` — funnel landing page (free chapters opt-in) → served at `/read`
- `FUNNEL.md` — funnel strategy + full email sequence copy
- `assets/` — images (see below)

## Required assets
These must exist in `assets/` or the site renders broken:

| File | What it is |
|---|---|
| `cursed-worlds-logo.png` | Emblem, transparent PNG |
| `cursed-worlds-hero.jpg` | Wide banner art, **no wordmark version** |
| `blood-elf-cover.jpg` | Book One cover |
| `favicon.png` | Square skull crop |
| `og-card.jpg` | 1200x630 social share image |
| `author.jpg` | Author portrait |

## Brand
Palette sampled from the series banner art — do not substitute Satyr Moon's gold/green.

| Token | Hex |
|---|---|
| night | `#06131a` |
| ghost cyan | `#8fd0de` |
| blood red | `#a51419` |
| bone | `#dfeaec` |
