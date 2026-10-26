# presentation-starter

A single-file, scrollable client pitch deck template. Pure HTML + inline CSS + vanilla JS - no build step, no dependencies beyond Google Fonts. Host it anywhere static (GitHub Pages, Vercel, Netlify) or just open index.html in a browser.

## What's inside

- 8 full-screen sections with snap-scroll feel: hero with clickable index, Website Development, SEO, Domain, Hosting, Analytics, Meta/GA integration, Meta Ads
- Dark/light alternating sections, gold accent, premium typography (Inter + Playfair Display)
- Fixed brand header and clickable pagination dots that adapt to dark/light sections automatically
- Smooth-scroll navigation via IntersectionObserver (no libraries)

## Customize for a new client

1. Copy `index.html` (or use GitHub's "Use this template" button above to spawn a fresh repo).
2. Replace the placeholders:
   - `[Client Name]` - in the `<title>` tag and the hero heading (2 spots)
   - `yourclientdomain.com` - the client website link in the Website Development section (2 spots: href + link text)
3. Optional: edit section copy to match your offer, add/remove sections (remember to update the nav dots and the index list - they are position-indexed).
4. The header brand line (`Ratnanjali TechX Private Limited`) is the agency brand - leave as is or swap it.

## Notes

- Section numbering (`01`-`07`) is hand-written in the markup; keep it in sync if you reorder.
- Tested pattern across several client decks; works on mobile (responsive grid + dots).
