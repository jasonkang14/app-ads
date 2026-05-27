# Kangsium

Landing page and ad-network configuration for [Kangsium](https://app.kangsium.com) indie mobile games.

Hosted via GitHub Pages at **[app.kangsium.com](https://app.kangsium.com)**.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | Static landing page listing the games, with links to their Google Play listings. |
| `app-ads.txt` | Authorized sellers declaration ([app-ads.txt spec](https://iabtechlab.com/ads-txt/)) for AdMob/Google Ads. |
| `CNAME` | Custom domain (`app.kangsium.com`) for GitHub Pages. |

## Games

| Game | Status | Play Store |
| --- | --- | --- |
| Memory Match | Live | [com.kangsium.memory_match](https://play.google.com/store/apps/details?id=com.kangsium.memory_match) |
| Cactus Hop | Live | [com.kangsium.cactus_hop](https://play.google.com/store/apps/details?id=com.kangsium.cactus_hop) |
| Neon Bricks | Live | [com.kangsium.neonbricks](https://play.google.com/store/apps/details?id=com.kangsium.neonbricks) |
| Neon Snake | Live | [com.kangsium.neonsnake](https://play.google.com/store/apps/details?id=com.kangsium.neonsnake) |
| Color Match Tap | Coming Soon | — |
| Fortune Cookie | Coming Soon | — |

## Development

This is a single static HTML file with inline CSS — no build step. Edit `index.html`
directly and open it in a browser to preview. Changes pushed to `main` deploy
automatically via GitHub Pages.
