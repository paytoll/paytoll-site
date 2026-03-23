# PayToll

Monetize any API with machine payments.

The open-source developer toolkit for accepting payments from AI agents, apps, and humans on Solana. Built on the [Machine Payments Protocol (MPP)](https://mpp.dev).

## What is this repo?

This is the marketing site and documentation for PayToll. Static HTML deployed on Vercel.

## Deploy

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

Or push to GitHub and connect to Vercel for automatic deployments.

## Structure

```
paytoll-site/
├── index.html          # Full SPA — home, blog, docs, pricing
├── assets/
│   ├── solana.svg       # Solana logo
│   └── stripe.svg       # Stripe logo
├── vercel.json          # Vercel deployment config
└── README.md
```

## Pages

All pages are handled via client-side routing in a single HTML file:

- **/** — Landing page with product overview
- **blog** — Blog posts on machine payments
- **docs** — Full SDK documentation
- **pricing** — Free, Pro, Enterprise tiers

## SDK

The actual PayToll SDK lives at [github.com/paytoll/sdk](https://github.com/paytoll/sdk) (coming soon).

## License

MIT
