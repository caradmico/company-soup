# Stack inventory · Company Soup

**Soup Ops · STRUCTURE lens · curated 2026-09-10**

Ventures, hosts, language, and Decap/Sveltia fit. Not a dashboard redesign. Machine copy: [`stack-inventory.json`](./stack-inventory.json). Pages: [ops/stack-inventory.md](https://caradmico.github.io/company-soup/ops/stack-inventory.md).

## Decap / Sveltia

| Fit | Surfaces |
|---|---|
| **yes** | _none on Soup static — Coast Desk is the HERO Decap/Sveltia pilot, still maybe until lit_ |
| **maybe** | **coast-desk** (HERO Decap pilot — bylines/clips), grant-desk (resources JSON), signal-shelf (md briefs), fine-art (works metadata), ops/links (`links.json`) |
| **no** | **food-desk** (Drive-private / HARD PRIVACY — not the public Decap pilot); shops, Firebase / Three.js apps, pure brand packs, redirects, ops surfaces, WP-gone / external hosts |

## Doors (in `doors.json`)

| id | name | live | host | stack | decap |
|---|---|---|---|---|---|
| fine-art | Neahkahnie Atelier | [Pages](https://caradmico.github.io/company-soup/businesses/fine-art/) | GitHub Pages | HTML/CSS + `works.js` (static gallery) | maybe — works metadata |
| demeter-watershed | Demeter Design | [Pages](https://caradmico.github.io/company-soup/businesses/watershed/) | GitHub Pages | static HTML; proof PDFs still on legacy graphicoregon.com `/wp-content/` | no — firm door + WP-gone PDFs. `demeterdesign.net` cert mismatch / not reliable |
| coast-desk | Coast Desk | [Pages](https://caradmico.github.io/company-soup/brands/coast-desk/) | GitHub Pages | static HTML + `clips.json` | maybe — HERO Decap/Sveltia pilot (bylines/clips; still maybe until lit) |
| grant-desk | Grant Desk | [Pages](https://caradmico.github.io/company-soup/brands/grant-desk/) | GitHub Pages | static HTML + resources JSON | maybe — resources JSON. Public face: training-day ~$250 (not consulting) |
| food-desk | Food Desk | [Pages](https://caradmico.github.io/company-soup/brands/food-desk/) | GitHub Pages | static HTML + `posts/*.html` | **no** — Drive-private / HARD PRIVACY; not the public Decap pilot |
| graphic-oregon | Graphic Oregon (Soup brand door) | [Pages](https://caradmico.github.io/company-soup/brands/graphic-oregon/) | GitHub Pages | static HTML pack | no — brand pack |
| sassmeharder | Sassmeharder | [shop](https://sassmeharder.com/) | Printify (nginx / Printify) | Printify-hosted Next.js — not Soup static | no — shop |
| staris | StarIS | [Firebase](https://staris-b01f2.firebaseapp.com/) | Firebase Hosting | Three.js web app | no — Firebase / Three.js |
| asterism-lab | Asterism Lab | [Pages](https://caradmico.github.io/company-soup/brands/asterism-lab/) | GitHub Pages | static HTML (links out to StarIS) | no — brand pack |
| far-field-media | Far Field Media | [Pages](https://caradmico.github.io/company-soup/brands/far-field-media/) | GitHub Pages | static HTML; sample video on legacy GO `/wp-content/` | no — brand pack + WP-gone media |
| signal-shelf | Signal Shelf | [Pages](https://caradmico.github.io/company-soup/brands/signal-shelf/) | GitHub Pages | static HTML + md sample | maybe — md briefs |
| lane-sites | Lane Sites | [Pages](https://caradmico.github.io/company-soup/brands/lane-sites/) | GitHub Pages | static HTML (explicitly bans Three.js CONTINUE) | no — brand pack |

## Ops surfaces (not all in `doors.json`)

| id | name | live | host | stack | decap |
|---|---|---|---|---|---|
| company-soup-root | Company Soup root cooker | [Pages](https://caradmico.github.io/company-soup/) | GitHub Pages | static HTML | no — cooker |
| ops-dashboard | Soup Ops dashboard | [Pages](https://caradmico.github.io/company-soup/ops/dashboard/) | GitHub Pages | static HTML + JSON (doors / factory / objects / flight) | no — ops surface |
| ops-links | Ops link shelf | [Pages](https://caradmico.github.io/company-soup/ops/links/) | GitHub Pages | static HTML + `links.json` | maybe — `links.json` |
| ops-autonomy | Autonomy OS | [Pages](https://caradmico.github.io/company-soup/ops/autonomy/) | GitHub Pages | static HTML + md pack | no — ops md pack |

## Related / omitted

| id | name | live | host | stack | decap |
|---|---|---|---|---|---|
| graphicoregon-com | graphicoregon.com | [CF front](https://graphicoregon.com/) | Cloudflare (WP-gone) | legacy `/wp-content/` still used by Soup doors | no — external |
| nccwp-map | NCCWP · Nehalem map | [Pages](https://caradmico.github.io/graphicoregon/nccwp/) | GitHub Pages | HTML + Leaflet + GeoJSON | no — omitted from doors board |
| orbit-creek | Orbit creek | [Pages](https://caradmico.github.io/graphicoregon/creek/) | GitHub Pages | HTML + Three.js (`vendor/three.min.js`) | no — Three.js sister repo |
| houseme-rentme | HouseMe / RentMe | — | none | no public door | no — note only |

## Redirects (demoted — still on tree)

| id | name | live | points to | decap |
|---|---|---|---|---|
| estuary-ink | Estuary Ink | [Pages](https://caradmico.github.io/company-soup/brands/estuary-ink/) | Company Soup root | no — redirect |
| quiet-cut | Quiet Cut | [Pages](https://caradmico.github.io/company-soup/brands/quiet-cut/) | signal-shelf | no — redirect |
| netarts-systems | Netarts Systems | [Pages](https://caradmico.github.io/company-soup/brands/netarts-systems/) | demeter-design | no — redirect |

Soup Ops owns the structure lens. Dashboard KEEP look stays closed.
