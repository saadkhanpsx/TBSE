THE BOOK SIGNING EVENTS (TBSE) — WEBSITE

Files
- index.html: one-page site (light vanilla JavaScript).
- privacy.html, terms.html: Privacy Policy and Terms of Service, linked from the footer and from both forms.
- assets/css/site.css: shared stylesheet for all three pages.
- assets/brand, assets/case-studies, assets/events: logo, author photos, signing-day video.

Preview: open index.html in a modern browser (Google Fonts load when online).

Before launch
1. Forms: both forms (popup and contact section) validate in the browser and show a thank-you state, but do not deliver submissions until FORM_ENDPOINT (top of the script in index.html) is set to a form service or CRM webhook such as Formspree.
2. Replace the demo phone number +1 (212) 555-0148 (contact section and footer).
3. Facebook and Instagram footer icons currently link to "#". Add the real profile URLs.
4. Add canonical/share-image meta tags once the domain is known.
5. Have counsel review privacy.html and terms.html. Terms now follow the supplied event contract (Phase 1 fee, $100 fee only after B&N approval, refund policy, responsibilities). Sections on media use, ownership, liability and governing law are drafted from general understanding; governing law points to the signed service agreement until a state is chosen.

Revision notes (round 4)
- Header: darker bar, oversized round logo that overlaps the bar and shrinks to a compact size when scrolling.
- Every "Reserve your spot" button opens the popup form. Package buttons read "Get pricing" and open the same popup with the package noted.
- Hero, intro, comparison, phases, FAQ, contact and footer rewritten in a confident, professional voice.
- Packages: First Time Author Package and Elite Author Package with the supplied feature lists; pricing removed. Elite-only upgrades are marked with a star.
- Contact form: same fields as the popup plus book title, book link and author introduction; button "Send my application".
- Footer: Reach section removed, social icons placed under Get in touch, new brand paragraph.
- Developer notes, sample tags and placeholder text removed from the visible site.

Revision notes (round 5)
- More space above the header logo; contact form rebalanced into even rows with a published-author dropdown.
- Popup left panel: large centered logo, short proven-process copy, 12 / 320+ / 31 stats.
- Disclaimer reduced to a slim two-line band; section headings fit two lines on desktop and tablet.
- Comparison chart redesigned; contact section made compact and aligned.
- "Back to top" and logo links now scroll to the top of the page.
- Terms updated from the contract; payment wording is an upfront Phase 1 fee plus a $100 fee only after B&N approval.

ROUND 6
- State is now a free-text field in both forms.
- Package 2 ribbon reads "Bestseller".
- Consent line sits on one line (scales slightly on narrow screens, wraps on phones).
- Packages redesigned: icon header, key-stat tiles, grouped sections, gold-highlighted Elite upgrades.
- Subtle motion added (entrance fades, hover lifts, button sheen, gentle float). Respects reduced-motion settings.

ROUND 7
- Scrolled header logo now overhangs the bar clearly.
- Mobile: menu opens above the logo, popup scrolls fully, small-screen package tweaks, no sideways scroll.
- Footer social icons keep their icon on hover.

ROUND 8 (SEO)
- New title, meta description, canonical, robots, social-share tags and 1200x630 share image (assets/seo).
- Structured data: Organization (logo), WebSite, WebPage, Service, FAQ. Added robots.txt, sitemap.xml, PNG favicons.
- Social links: facebook.com/thebooksigningevents and instagram.com/thebooksigningevents (footer icons + schema).
- Assumes the live domain is https://thebooksigningevents.com/ - change it in index.html, privacy.html, terms.html, robots.txt, sitemap.xml if different.
- Footer now shows Location: Los Angeles, CA (also in schema).
