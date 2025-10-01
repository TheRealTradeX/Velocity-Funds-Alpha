# Velocity Funds — Static Site Template

This is a clean, responsive static template you can open directly in VS Code and deploy on Netlify/Vercel/S3 or behind any backend.

## File Structure
.
├── index.html
├── challenges.html
├── rules.html
├── faq.html
├── leaderboard.html
├── about.html
├── contact.html
├── careers.html
├── privacy.html
├── terms.html
├── risk-disclosure.html
├── dashboard.html
├── checkout.html
└── assets
    ├── css
    │   └── styles.css
    ├── images
    │   ├── logo.svg
    │   └── hero-chart.png  (replace with your chart/hero image)
    └── js
        └── main.js

## Branding & Assets
- Replace `/assets/images/logo.svg` with your Velocity Funds logo (same filename).
- Replace `/assets/images/hero-chart.png` with your hero image or screenshot.
- Add more images in `/assets/images/` and reference them in HTML.

## Colors & Styles
Edit `/assets/css/styles.css` and Tailwind utility classes in the HTML.
Primary accent is `#34D399` (emerald). Background is black/neutral.

## Pricing & Rules
- Update pricing numbers in `index.html` (Pricing section) and `challenges.html`.
- Update risk parameters in `rules.html`.

## Leaderboard / Dashboard
The `leaderboard.html` and `dashboard.html` are placeholders. Wire them to your data/API.
You can convert this to a framework later (Next.js/React) if needed.

## Deployment
- Static hosting: just upload the folder as-is.
- Nginx/Apache: serve the folder root.
- Netlify: drag-and-drop or connect a repo.
- Vercel: deploy as static assets.

## Notes
This template mirrors the *structure and UX patterns* you referenced without copying any proprietary content. Replace placeholder copy with your own.
