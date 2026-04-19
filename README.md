# Your Sports BFF (S*BFF)

Female-first sports media brand. The home court advantage for the women who watch, the ones who want to, and everyone in between.

## Structure

Single-page static site:

- `index.html` — homepage (all markup, CSS, and minor JS embedded)
- `vercel.json` — clean URL configuration for Vercel deployment
- Images — hero, manifesto pills, polaroid strips, values grid

No build step. No dependencies. Open `index.html` in any modern browser to preview.

## Deploying to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com/new](https://vercel.com/new) and import the repo
3. Framework preset: **Other** (or "Static")
4. Root directory: `./`
5. Build command: leave blank
6. Output directory: leave blank
7. Deploy

`vercel.json` handles clean URLs (so `/bff-brief` works without the `.html` extension once those pages are added).

## Design system

| Token            | Value    | Usage                            |
| ---------------- | -------- | -------------------------------- |
| Mandarin         | #FE6735  | Primary accent, italic emphasis  |
| Mandarin dark    | #E55A2D  | Hover state for CTAs             |
| Charcoal         | #1E1C1A  | Primary text, dark backgrounds   |
| Stone            | #FEFEFE  | Page background                  |
| Pink             | #FFE1EE  | Subtle accent                    |

- Display font: **Perfectly Nineties** (embedded as base64 in the HTML)
- Body / UI: **Manrope** (loaded from Google Fonts)

## Still to do

- BFF Brief detail page (`bff-brief.html`)
- About page (`about.html`)
- Account / member area (`account.html`)
- Social feed integration (Instagram/TikTok) — placeholder cards currently in place
- Remaining polaroid card images if any
- Copy review on CTA banner and footer
- MemberStack auth integration
- Airtable + Zapier for BFF Brief SMS signup

## License

All rights reserved.
