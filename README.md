# Freemen Provisions — Business Website

Static business website for Freemen Provisions (agricultural consulting, services & products).
Built to support the Stripe account application: includes customer service contact details,
return policy, refund & dispute policy, cancellation policy, legal/export restrictions,
promotions terms, terms of service, and privacy policy.

## Run locally

```
node server.js
```

Then open http://localhost:3000 (or set `PORT`).

## Deploy

Any static/Node host works. On Railway: deploy from this repo — Nixpacks detects Node,
`npm start` serves the site. Set a public domain (e.g. freemenprovisions.com or
freemen-provisions.up.railway.app) for the Stripe application.

## Structure

- `index.html` — home
- `services.html` / `products.html` — offerings
- `contact.html` — contact details + contact form (opens the visitor's email app)
- `returns.html`, `refunds.html`, `cancellations.html`, `promotions.html`, `terms.html`, `privacy.html` — policies
- `styles.css` — shared design system
- `server.js` — tiny dependency-free static file server

## Contact details

The email (`contact@freemenprovisions.com`), phone (`(555) 013-0142`), and address
(`123 Harvest Lane, Yourtown, ST 00000`) are placeholders — replace with the real
business details before submitting the Stripe application.
