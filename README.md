# Spare Hour website

Static one-page site for Spare Hour by Adrian Patterson. Served by GitHub Pages from `main` (root).

- `index.html`: the whole site (styles and script inline)
- `adrian.jpg`: About portrait
- `favicon.svg`, `apple-touch-icon.png`, `og-image.jpg`: icons and the link-preview card

Booking button points to https://calendly.com/adrianlpatterson/30min (set in `BOOKING_URL` near the bottom of `index.html`).

## Brand guidelines

`brand/index.html` is the brand book: logo, colour, type, site pieces, motion, voice and where each file lives. It is served at `/brand/` (not indexed by search engines). Its colours and fonts come from the `:root` block in `index.html`; if the two disagree, the site wins and the brand page gets updated.
