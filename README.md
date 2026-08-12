# Teia, The Ecosystem Around an NFT

A one-page, living map of everything that grows around a single NFT on [teia.art](https://teia.art) — from minting and rights through discovery, connection, and community governance. It tracks what's live on Teia today and what's coming, with each feature linked to its source.

**→ [View it live](https://pixelsushirobot.github.io/Teia-Ecosystem/)**

## What it is

Everything on the page builds around one anchor: **a single NFT on teia.art**. From there it walks through five stages of the ecosystem, each with the concrete features that live in it and the roles those features serve.

1. **Create** — the work exists, with rights defined (Mint, Collaborations, License at Mint)
2. **Rights & Value** — the work earns and its rights become usable (Resale & Royalties, Copyright Registration, Copyright Marketplace, Distribution Deals)
3. **Discover & Collect** — the work gets seen and collected (Activity, Feeds & Discovery, Curation, Curation Fees)
4. **Connect** — the work connects people directly (Direct Messages, Channels, Token-Gated Comments, Notifications)
5. **Community & Govern** — the work plugs into a self-run community (Community Wiki, Calendar, Polls, DAO Governance)

Each feature is tagged with the roles it serves — `#artist`, `#collector`, `#curator`, `#brand` — color-coded consistently across the page.

## Living reference

The page is meant to be updated as features roll out, so it stays an accurate picture of what Teia can do. Each feature card sits in one of three states, shown by its tag:

- **Live** (no tag) — available on the main app now. Source links to its teia.art page.
- **`Preview`** — usable on `preview.teia.art` but not yet on main. Source links to the preview route. When it ships, drop the `Preview` tag and repoint the link from `preview.teia.art` to `teia.art`.
- **`Soon`** — announced but not yet functional. Source links to a founder/dev post. When it ships, drop the `Soon` tag and repoint to the live route.

Each card also has a **source link** — a link icon (top-right, appears on hover) pointing to its source: a teia.art page, a preview route, or a founder/dev post.

## Features

- **Single self-contained file** — all HTML, CSS, and JavaScript inline in `index.html`. No build step, no dependencies, no external requests.
- **Light / dark / system theme toggle** — top-right of the header. Defaults to following your OS; your choice persists via `localStorage`.
- **Per-card source links** — a link icon on each card (dimmed, brightens on hover; always shown on touch) opening the feature's source in a new tab.
- **Responsive** — two-column card grid collapses to one column on narrow screens.
- **Print-friendly** — a print stylesheet keeps cards and stages from breaking across pages; the theme toggle and source icons are hidden when printing.
- **Share-ready** — Open Graph and Twitter card meta tags for clean link previews, plus light/dark `theme-color`.

## License

MIT
