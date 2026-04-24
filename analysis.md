# Klaus Reinke Website Analysis

## Color Palette (from Elementor CSS)

| Token | Hex | Usage |
|-------|-----|-------|
| Primary | `#F2EEEB` | Warm off-white, main background |
| Secondary | `#BFAB99` | Warm beige, text accents |
| Text | `#F2AB6D` | Peach/orange accent |
| Accent | `#1C4003` | Deep forest green, headings, links |
| Green-2 | `#5C734C` | Muted sage green, backgrounds, dividers |
| Mid-green | `#708860` | Slightly brighter sage |
| Sidenav BG | `#F4D3B5` | Warm peach/beige for mobile nav |
| Dark overlay | `#081400` | Near-black green for hero overlay |
| Burger fill | `#F4D3B5` | Same as sidenav |

## Typography

| Role | Font | Weight | Notes |
|------|------|--------|-------|
| Headings (h1,h2) | IBM Plex Sans | 400–600 | Large display |
| Body / paragraphs | IBM Plex Serif | 400 | Also italic for taglines |
| Accent text | IBM Plex Serif | 400 italic | Subheadings |

## Layout Structure

1. **Hero** (`#start`) — full viewport, background dandelion image, logo top-right, hamburger top-left, headline bottom-left
2. **About** (`#ueber-mich`) — green background (`#1C4003`), heading, divider, intro text, accordion with personal bio, photo
3. **Philosophy** (`#philosophie`) — beige background (`#5C734C`), heading, text, photo with dandelion overlay
4. **Testimonials** (`#kunden`) — green background, heading, Swiper carousel with 2 slides visible (desktop), 1 (mobile)
5. **Services / Offer** (`#angebot`) — green background, heading, list of services with alternating sage/muted-sage cards
6. **Contact** — full-bleed background image with dark overlay, large italic text CTA
7. **Footer** — minimal, links to Impressum, Datenschutz, Cookie-Richtlinie, AGB

## Navigation

- Desktop: fixed hamburger icon (SVG, left side) + logo top-right
- Mobile side nav (`sidenav`) slides in from left, width 300px, peach background
- Links: start, über mich, meine philosophie, rezensionen, leistung, meinungen, phone, impressum, datenschutz, cookie-richtlinie, agb

## Interactive Elements

- **Accordion** on "Über mich" section ("mehr zu mir") — expands to show personal bio
- **Testimonial carousel** — Swiper-based, autoplay likely, pagination dots
- **Scroll-to-top** button
- **Side nav** open/close with JS width toggle

## Images Used

| File | Description |
|------|-------------|
| loewenzahn.webp | Hero background, dandelion field |
| redewert_logo_gruen-1-1024x1024.png | Green logo icon |
| redewert_logotype_weiss-768x295.png | White logotype text |
| Klaus-Reinke-768x767.png | About section portrait |
| klaus_reinke-743x1024.webp | Tall portrait (newer) |
| kleine-blumenpflanzen-mit-sonnenuntergang-und-bergen-1536x1024.jpg | Contact section background |

## Pages

- `/` — Homepage
- `/impressum` — Legal notice
- `/datenschutz` — Privacy policy
- `/cookie-richtlinie` — Cookie policy
- `/agb` — Terms
- `/meinungen` — Testimonials page
