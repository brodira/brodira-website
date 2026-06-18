# BRODIRA – Website (Deploy Now)

Static B2B one-pager for **brodira.de**. All SEO quick wins are implemented in code.

## Files
- `index.html` — homepage (single H1, schema, FAQ, CTAs, optimized title/meta, image alt text)
- `impressum.html` · `datenschutz.html` — legal pages
- `robots.txt` · `sitemap.xml`
- `assets/` — logo + 6 product photos as WebP (~264 KB total)
  - NOTE: `assets/` also still contains the original large `.png` source files. **Delete the `.png` files before deploying** (keep only `.webp` + `icon-1024.png`) to keep the repo small. They aren't referenced by the site.

## What's built in (the SEO quick wins)
- ✅ **One `<h1>`** — the keyword tagline only
- ✅ **Title** "Stickerei Karlsruhe für Firmen – Logo besticken | BRODIRA" + B2B meta description
- ✅ **LocalBusiness + FAQPage JSON-LD schema**
- ✅ **Open Graph** tags + favicon
- ✅ **CTA buttons** ("Angebot anfordern") in header, hero and contact
- ✅ **Click-to-call** phone (`tel:`) and correct **info@brodira.de**
- ✅ **Real product photos with keyword alt text** (WebP, lazy-loaded)
- ✅ **FAQ section** (MOQ, price, logo, lieferzeit, material)
- ✅ Responsive, fast, no cookies/tracking

## Deploy to IONOS Deploy Now (free static tier)
1. Create a **GitHub repo** (e.g. `brodira-website`) and push the contents of this folder to it (after deleting the `.png` sources in `assets/`).
2. In your IONOS account → **Deploy Now** → **Create project** → connect the GitHub repo.
3. Build settings: **no build step** (static HTML). Output/Publish directory: the repo root (where `index.html` is).
4. Deploy → you get a temporary `*.ionos.space` URL to preview.
5. Point **brodira.de** to the Deploy Now project (IONOS guides you through the DNS/domain connection). The domain is currently on the MyWebsite Now Plus contract — you'll repoint it to Deploy Now.

## Recommended follow-ups (from the SEO audit)
- Self-host the Google Fonts to remove the external font request (full DSGVO cleanliness) — optional.
- Add a Google Business Profile for "Stickerei Karlsruhe".
- Later: add dedicated pages (Stickerei Karlsruhe, Logo-Stickerei, audience pages) — the strategic investments in the audit.
