# BraimSec website — for Paddle verification

Static site (no build step): `index.html`, `pricing.html`, `terms.html`,
`privacy.html`, `refunds.html` + `assets/style.css`.

## Before submitting URLs to Paddle — replace these

| Placeholder | Replace with | Files |
|---|---|---|
| `support@braimsec.com` | Real support email | all HTML files |
| "Braim, an individual business" | Legal entity name if it changes | terms, privacy |
| "governed by the laws of Lebanon" | Confirm with your situation | terms.html |
| 30-day scan retention | Confirm matches actual policy | privacy.html |
| Scan quotas (100 / 1,000 / 10,000) | Must match what billing enforces (Phase 2 wiring) | pricing.html |

Pricing on the page matches the live Paddle catalog exactly:
Starter $10/mo $100/yr · Pro $40/mo $400/yr · Advanced $120/mo $1,200/yr.

## Hosting (pick one, ~5 minutes)

**Option A — Netlify Drop (easiest):**
1. Go to app.netlify.com/drop
2. Drag the whole `braimsec-site` folder into the page
3. You get a public URL like `https://braimsec-xxxx.netlify.app`
4. Optional: Site settings → Change site name → `braimsec`

**Option B — GitHub Pages:**
1. Push this folder to a repo, Settings → Pages → Deploy from branch

## Then in Paddle

Developer Tools → verification form:
- Pricing page: `https://YOUR-URL/pricing.html`
- Terms: `https://YOUR-URL/terms.html`
- Privacy: `https://YOUR-URL/privacy.html`
- Refunds: `https://YOUR-URL/refunds.html`

Also submit the domain for checkout approval: Checkout → Website approval.
