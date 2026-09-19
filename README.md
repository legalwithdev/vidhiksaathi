# Vidhiksaathi

Vidhiksaathi's official website — a static site with **no build step, no dependencies**. Just open `index.html`.

## Features

- **Brand:** dark navy blue & white
- **Default language:** English
- **13 languages:** English, हिन्दी, বাংলা, मराठी, ગુજરાતી, ਪੰਜਾਬੀ, ଓଡ଼ିଆ, தமிழ், తెలుగు, ಕನ್ನಡ, മലയാളം, اردو, অসমীয়া — via the globe button (🌐 Language) in the navbar. Choice is saved in the browser (localStorage). Urdu renders right-to-left automatically.
- Mobile responsive, FAQ accordion, services grid, process steps, CTA, footer + legal disclaimer
- Graceful degradation: with JavaScript off, the site shows in English

## Files

- `index.html` — page structure + styles + language switcher logic
- `lang1.js` — translations: en, hi, bn, mr, gu, pa
- `lang2.js` — translations: or, ta, te, kn, ml, ur, as

## Deploy on Cloudflare Pages

1. [dash.cloudflare.com](https://dash.cloudflare.com) → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**
2. Select this repository (`vidhiksaathi`)
3. Project name: **vidhiksaathi** (so the URL becomes `vidhiksaathi.pages.dev`)
4. Build settings — leave empty: Framework preset **None**, no build command, output directory `/`
5. **Save and Deploy** — live at `https://vidhiksaathi.<your-subdomain>.pages.dev`

Every push to this repo now auto-updates the site.

## Custom domain

Cloudflare Pages project → **Custom domains** → add e.g. `vidhiksaathi.in`. Free automatic SSL.

## Before going live, replace

- Phone: `tel:+911234567890` (2 places)
- Email: `help@vidhiksaathi.in` (2 places)
- Stats (10,000+ / 50+ / 4.8/5) with real figures

## License

© 2026 Vidhiksaathi — All rights reserved
