# APS Concept V8 — Project Intelligence

A clean-sheet four-page design: light-first, technical and procurement-oriented. Not a production release.

## Architecture
- index.html, services.html, about.html, contact.html
- css/site.css
- js/site.js, js/us-map.js (unchanged from supplied map)
- assets/branding, assets/people, assets/favicons
- sitemap.xml, robots.txt

## Design decisions
- Light-first page with one dramatic dark map/field section and dark footer.
- Hero is an original SVG parcel/corridor *illustration*, explicitly marked not project data.
- Company history and experience are based on existing APS material, but presentation and copy are newly written. Verify all operational claims before publishing.
- Client marquee uses historic names as plain text. Official outbound links are not invented; add them only after verification.
- Form opens a prefilled mailto draft; it is not a secure server-side intake endpoint.
- Sitemap canonical paths assume Cloudflare Pages clean URL support. Verify before deployment.
- Google structured data and metadata are included, but search display features are not guaranteed.

## Launch checklist
Verify client references and claims, test at 320/375/768/1440 widths, keyboard access, map interactions, mobile menu, email-client handoff, and live URL canonicalization. No production deployment is implied.
