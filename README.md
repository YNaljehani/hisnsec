# Hisn — hisnsec.com

Marketing site for Hisn (حِصن) — Saudi cybersecurity practice for mid-market companies.

## Stack
- Static HTML + CSS + vanilla JS (single file)
- Tajawal font from Google Fonts
- Bilingual EN/AR with persistent toggle
- Netlify Forms backend for 3 intake forms (Readiness Check, vCISO inquiry, Scope inquiry)
- Hosted on Netlify, deployed from this GitHub repo

## Local preview
Open `index.html` in any browser. Note: forms submit only after deploy to Netlify (they need Netlify's backend).

## Deploy
Pushes to `main` auto-deploy via Netlify's GitHub integration.

## Form notifications
Form submissions email `hello@hisnsec.com` (configured in Netlify dashboard → Site settings → Forms → Notifications).
