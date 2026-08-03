# sites

Public one-page sites and customer-facing collateral, served via GitHub Pages.

**Live:** https://jessegorin.github.io/sites/

## Pages

| Path | Page | Use |
|------|------|-----|
| [`/google-search-ads/`](https://jessegorin.github.io/sites/google-search-ads/) | Google Search Ads — What They Do for Your Restaurant | QBR / onboarding one-pager for restaurant operators |
| [`/app-store-connect-access/`](https://jessegorin.github.io/sites/app-store-connect-access/) | Giving Chowly Access to Your App Store Account | iOS mobile app onboarding — customer-side App Store Connect setup |

## How it works

- Pages builds from `main`, root directory. Merging to `main` publishes.
- Each page is one self-contained `index.html` in its own folder — no build step, no dependencies, no external requests.
- Styling follows the Chowly v2 brand system (navy/blue/yellow, Lato headings, Inter body). Fonts fall back to the system stack; no CDN fonts.
- Every page is responsive, respects `prefers-color-scheme`, and has a print stylesheet so ⌘P produces a clean PDF handout.

## Adding a page

1. Branch off `main`.
2. Create `<slug>/index.html` as a complete standalone document.
3. Add a row to the table above and a card to the root `index.html`.
4. Open a PR.

## Source

Content on these pages is drawn from Chowly's internal Confluence documentation (TCP space). Rewritten for a customer audience — check the source docs before changing any figures.
