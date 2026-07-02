# Growth Offseason Offer — Landing Page

Single-file static landing page for the Growth "Offseason Offer" campaign (15% off, code 15OFF).

## Files
- `index.html` — the full landing page. Fonts, logos, and photos are embedded (base64), so it's a single self-contained file. The fence-sitter video streams from an unlisted YouTube link.
- `vercel.json` — sets a `noindex` header so the preview isn't picked up by search engines while it's password-gated.

## Password
The page is password-protected for preview. Password: `Offseason`
(This is a front-end gate for sharing previews, not real security — don't use it to hide sensitive info.)

## Deploying
Import this repo into [Vercel](https://vercel.com/new) and it deploys automatically — no build step, it's static HTML.

## Before going live
- Strip the password gate out of `index.html`
- Confirm the Circle checkout link in every CTA
- Double check the offer dates (currently Sun 5 Jul – Sun 12 Jul 2026)
