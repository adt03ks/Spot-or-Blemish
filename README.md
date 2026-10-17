# Spot or Blemish Catering — Website

A responsive, multi-section website ready for static hosting (GitHub Pages, Netlify, Cloudflare Pages, etc.). No backend required. Use `index.html` to start. The site navigates through URL hashes (`#menu`, `#chef`, etc.) so every page works on GitHub Pages without special routing.

## Publishing on GitHub Pages
1. Extract this ZIP. Create a new public or private GitHub repository and upload **all files and the `assets` folder** to the repository root.
2. Repository **Settings → Pages → Build and deployment → Deploy from a branch**. Select `main` and `/ (root)` and save.
3. Once published, update your custom domain DNS if desired. Add your domain in Pages settings and enable HTTPS once available.
4. Test the menu, estimate calculator, mobile navigation and all contact links.

## Edit these before going live
- `config.js`: business phone, email, social links, delivery fees, setup fees, service fee/hour, minimum order, and chef portrait path.
- `menu.js`: dish names, menu descriptions and starting prices. Suggested amounts are illustrative Houston-market planning prices, **not live competitor-verified data, vendor costs, or approved final quotes**.
- `assets/chef-archie.png`: replace with an actual photo of Chef Archie Speights; if missing, the site automatically shows a branded placeholder.
- `assets/archie-angela.png`: optional team image reserved for a future addition.
- `assets/spot-or-blemish-logo.png`: provided logo; retain file name to keep branding linked throughout.
- The food photos currently load from Unsplash external URLs for visual demonstration; **replace with your own photos and corresponding local image paths in `menu.js`** before commercial launch when possible. The hero photo is in `styles.css` under `.food-hero-image`.
- The wood finish in the top header is layered CSS grain rather than an actual photographed wood texture. For a photographic finish replace `.wood-bar` background with your own licensed wood photograph.

## Pricing + booking notes
Prices are currently per guest/per dish, with an illustrative $250 minimum. The quote builder multiplies each chosen dish by every guest, so it does not yet support half portions, tray ordering, tier volume discounts or split entrée selections. Headcount is limited to 500 for estimating; **75+ guests require special approval**. Food allergy accommodations, taxes, ingredients, serving sizes and service terms must be confirmed in the actual proposal. Delivery, setup and staffing calculations are estimates only; tax, rentals and gratuity are not calculated.

The form is **email draft only**, not a real booking system: clicking “Prepare Catering Inquiry” opens a prefilled email addressed to the configured business address. When no email is configured, it clearly prompts the visitor to copy the inquiry. It does not save personal data or process payments. For a production site with reliable lead submission, add an authenticated form endpoint, spam protection, and a privacy notice; use a compliant payment provider for deposits.

## Launch checklist
- [ ] Verify DBA/legal name and use of established year.
- [ ] Approve menu prices, portions, minimums, fees and service-area limits.
- [ ] Add phone, email and social accounts; test actual inquiry submission.
- [ ] Add licensed original food, chef and kitchen photography.
- [ ] Add your written booking/deposit, reschedule/cancellation, refund, food-allergy and privacy policies after legal review.
- [ ] Verify food business permits, food handling requirements, insurance, and sales-tax treatment with your Texas advisors.
- [ ] Check accessibility, keyboard navigation, mobile layouts, and image credits before advertising the site.
