# विधिक साथी — Vidhik Saathi

विधिक साथी की आधिकारिक वेबसाइट। यह एक single-page static site है — कोई build step नहीं, कोई dependency नहीं। सिर्फ़ `index.html`।

## Features

- पूरी तरह self-contained single file (`index.html`)
- हिंदी content — Mukta + Tiro Devanagari Hindi fonts
- Light और Dark mode (OS setting के हिसाब से automatic)
- Mobile responsive
- FAQ (expandable `<details>`), services grid, process steps, CTA, footer + legal disclaimer

## Cloudflare Pages पर deploy करें

1. [dash.cloudflare.com](https://dash.cloudflare.com) → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**
2. यह repository (`vidhik-saathi`) चुनें
3. Build settings में कुछ मत भरें:
   - Framework preset: **None**
   - Build command: *(खाली छोड़ें)*
   - Build output directory: `/` (या खाली)
4. **Save and Deploy** — website live हो जाएगी: `https://vidhik-saathi.<apka-subdomain>.pages.dev`

इसके बाद जब भी इस repo में `index.html` में बदलाव push करेंगे, website automatically update हो जाएगी।

## Custom domain

Cloudflare Pages project → **Custom domains** → **Set up a custom domain** (जैसे `vidhiksaathi.in`)। SSL free और automatic है।

## Deploy करने से पहले बदलें

- Phone number: `tel:+911234567890` (3 जगह)
- Email: `help@vidhiksaathi.in` (2 जगह)
- Stats (10,000+ / 50+ / 4.8/5) — अपने असली आँकड़ों से
- Address / about section — अपनी organisation की जानकारी से

## License

© 2026 विधिक साथी — सर्वाधिकार सुरक्षित
