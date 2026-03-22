# NumberCrunch Landing Page

Static HTML landing page for NumberCrunch — AI accounting back-office for CPA firms.

## Files

- `index.html` — Main landing page (dark navy + amber, 3-tier pricing)
- `pricing.html` — Standalone pricing page
- `numbercrunch.html` — Alt version (for A/B testing)
- `sample.html` — Sample deliverable preview

## Before You Deploy

1. **Stripe links:** Search for `#stripe-checkout` or `STRIPE_LINK` and replace with real Payment Link URLs
2. **Email:** `numbercrunch@agentmail.to` is live — no change needed

## Deploy (Netlify Drop — 30 seconds)

1. Go to https://app.netlify.com/drop
2. Drag the entire `landing/` folder into the drop zone
3. Done — live URL instantly

## Deploy (Vercel)

```bash
cd landing
npx vercel --yes
```

## Deploy (GitHub Pages)

Push `landing/` contents to a `gh-pages` branch of your repo.
