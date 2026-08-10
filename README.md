# Teia, The Ecosystem Around an NFT

A one-page map of everything that grows around a single NFT on [teia.art](https://teia.art) — from minting and rights through discovery, connection, and community governance.

**→ [View it live](https://pixelsushirobot.github.io/teia-ecosystem/)**

## What it is

Everything on the page builds around one anchor: **a single NFT on teia.art**. From there it walks through five stages of the ecosystem, each with the concrete features that live in it and the roles those features serve.

1. **Create** — the work exists, with rights defined (Mint, Collaborations, License at Mint)
2. **Rights & Value** — the work earns and its rights become usable (Resale & Royalties, Copyright Registration, Copyright Marketplace, Distribution Deals)
3. **Discover & Collect** — the work gets seen and collected (Activity, Feeds & Discovery, Curation, Curator × Artist Sales)
4. **Connect** — the work connects people directly (Direct Messages, Channels, Token-Gated Comments, Notifications)
5. **Community & Govern** — the work plugs into a self-run community (Community Wiki, Calendar, Polls, DAO Governance)

Each feature is tagged with the roles it serves — `#artist`, `#collector`, `#curator`, `#brand` — color-coded consistently across the page.

## Features

- **Single self-contained file** — all HTML, CSS, and JavaScript inline in `index.html`. No build step, no dependencies, no external requests.
- **Light / dark / system theme toggle** — top-right of the header. Defaults to following your OS; your choice persists via `localStorage`.
- **Responsive** — two-column card grid collapses to one column on narrow screens.
- **Print-friendly** — a print stylesheet keeps cards and stages from breaking across pages; the theme toggle is hidden when printing.

## Running it

It's a static page — open `index.html` in any browser, or host it anywhere that serves static files.

### GitHub Pages

1. Put `index.html` at the repo root.
2. **Settings → Pages → Build and deployment → Source: Deploy from a branch**, select `main` and `/ (root)`.
3. The site goes live at `https://<username>.github.io/<repo>/`.

## Credits

- Color system: [Reasonable Colors](https://www.reasonable.work/colors/) by Matthew Howell — used for the accessible role-tag palette.
- Theme-toggle pattern adapted from [fit.gif](https://github.com/PixelSushiRobot/fit.gif).

## License

MIT
