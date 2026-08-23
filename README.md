# Atlas Freight

A static marketing site for a global cargo / freight forwarding company — home, services & rates, about, and contact pages.

## Structure

- `index.html` — homepage
- `services.html` — services grid + indicative rates table
- `about.html` — company story, dark hero treatment
- `contact.html` — contact form + info
- `styles.css` — shared design system (colors, buttons, cards, responsive breakpoints)

No build step or dependencies — open `index.html` directly in a browser, or serve the folder with any static file server.

## Before going live

Several placeholders still need real values — search each HTML file for bracketed text:

- `[YOUR PHONE NUMBER]`, `[YOUR BUSINESS HOURS]`, `[YOUR EMAIL]`, `[YOUR ADDRESS]`
- `[PRICE]` in the services rates table
- `[X,XXX]+ clients` trust stat on the homepage

The contact form (`contact.html`) is markup only — it doesn't submit anywhere yet and needs a backend or form service wired up.

"FAQ," "Track a Shipment," and "Watch company video" are placeholder links (`#`) since those pages/features haven't been built yet.
