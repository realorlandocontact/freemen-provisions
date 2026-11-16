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

Real email (freemenpro@pm.me) and phone ((407) 704-0240) are on the site. No business
address is published yet — add one to contact.html / terms.html / privacy.html when available.
