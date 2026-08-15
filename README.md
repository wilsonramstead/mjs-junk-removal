# MJ's Cheap Junk Removal — website

Demo marketing site for **MJ's Cheap Junk Removal**, an owner-run junk removal &
hauling business in Port Richey, FL, serving Pasco County and the Tampa Bay area
(junk removal & hauling, furniture/mattress/appliance haul-away, and garage/estate
cleanouts).

- **Live:** https://wilsoninnovations.net/mjs-junk-removal/
- **Live (Pages):** https://wilsonramstead.github.io/mjs-junk-removal/
- **Phone / Text:** (727) 859-5360 → `tel:+17278595360` / `sms:+17278595360`
- **Address:** 7203 Seward Dr, Port Richey, FL 34668 (Pasco County — home-based service business)
- **Rating:** 4.6★ · 16 Google reviews (shown — ≥4.4; presented, not over-emphasized)
- **Owner referenced in reviews:** George (owner-operator). "MJ" is the business
  nickname — referenced factually, no owner-personality section.

## Facts used (verified — manifest / Google Business Profile / their own GBP photo)
- Business name kept as **MJ's Cheap Junk Removal** — "Cheap" is part of their real
  name; leaned into honest value positioning (flat rates, fair pricing) with **no
  invented prices**.
- Services (supported by real reviews + the trade): furniture & mattress removal,
  appliance & bulky-item haul-away, general junk & clutter, garage/estate/property
  cleanouts, yard & storm debris, single item to full trailer load. Reviews
  explicitly corroborate: furniture & mattresses, general pre-move junk, full loads
  ("everything that was going WENT"), the crew does the loading, fast text booking,
  same-day/next-day pickups.
- **Equipment facts from their own GBP photo (verbatim from the graphic):** a
  10-yard dump trailer — **12 ft long, 6 ft wide, 4-ft sides = 10 yards**, with a
  **ramp for easy loading**; **flat rates**; serves **Pasco County**. The real
  trailer photo (cropped) is used in the "How it works" section.
- Value language ("great rates," "won't charge an arm and a leg," "reasonably
  priced," "fair rates") is drawn from the reviews, not invented.
- **Reviews** are real Google reviews, quoted near-verbatim (light normalization of
  spelling/spacing only), attributed by first name + last initial (Krystal J.,
  Dianne P., Vincent, Dean D.) — plus the reviewer's real Google display name
  "Darkcloudking" shown as-is (no name fabricated). No review card was invented; the
  dark 6th card is an explicit call-to-action (no stars, no quote styling), not a
  testimonial.

## NOT claimed (left out — unverified)
- No prices/rates quoted (name says "cheap" but no numbers were invented).
- No license number, no founding year, no email (none published on GBP).
- **Hours anomaly softened:** GBP lists Mon–Sun 7 AM – 8 PM (owner-cell, always-on).
  Presented plainly in the footer as "Mon–Sun 7 AM – 8 PM" and messaged as
  "same-day & next-day pickups, 7 days a week" — **no literal 24/7 claim**.
- The residential address is in JSON-LD + a light footer line only — not presented
  as a walk-in storefront.

## Design
- **Tier 1 — Clean Slate** with an industrial hauler edge: white/soft-steel base,
  charcoal bands, and a **high-vis safety-yellow** accent (palette hint: bold
  charcoal + steel with high-vis yellow accent).
- **Fonts:** Oswald (display, condensed) + Public Sans (body) — approved pair,
  Google Fonts.
- Single self-contained `index.html` (inline CSS + minimal vanilla JS); works from
  `file://` and with JS off.
- Full hero stack (eyebrow → headline → sub → CTA pair → glass trust chip) visible
  with no scroll at 1440×900 and 1366×768. Reduced-motion-aware scroll reveals +
  Ken Burns hero.
- Header call/text CTA flush right, **icon-only ≤600px**. **No fixed bottom mobile
  call bar.**
- `noindex` while in demo; LocalBusiness JSON-LD with aggregateRating 4.6/16; Open
  Graph / Twitter absolute URLs at https://wilsoninnovations.net/mjs-junk-removal/
  (og:image = hero) for DM link previews.
- Verified: puppeteer-core + Edge at true 390 / 1366×768 / 1440×900 — zero
  horizontal overflow; every screenshot reviewed; all images load and match alts.

## Image credits
Own photo re-encoded ≤350KB; Unsplash stock self-hosted, re-encoded ≤350KB. All
Unsplash IDs dedup-greped against websites/*/index.html + websites/*/README.md +
templates/*/ immediately before download AND before commit (unused IDs only), and
phash-compared (dhash-16, min 104/256 — SAFE, ≥25) against the unknown-ID folders
(woods-fencing, da-costa-construction, coastal-irrigation, out-fox-welding,
marquez-pavers) plus junk siblings. Every image visually reviewed against its alt.
- trailer.jpg — **their own GBP photo** (cropped): MJ's real wooden 10-yard dump
  trailer lettered "Cheap Junk Removal · Pasco County."
- hero.jpg / og-preview.jpg — photo-1692029659415-91dd91576be4 (old furniture set out at a residential curb for pickup)
- haul-furniture.jpg — photo-1560843300-ce9370f96b56 (an old sofa dumped against a wall)
- haul-cleanout.jpg — photo-1648598860632-dbb13eb848d6 (a large pile of household junk cleared from a yard)
- haul-curb.jpg — photo-1682207475669-2e718b3a6a20 (a worn armchair set out on the street)
- haul-appliance.jpg — photo-1751177911267-cf29825e0c68 (old ovens/appliances stacked and discarded)

## Placeholders to swap after sale
- All stock imagery is Unsplash placeholder — swap for MJ's own job photos.
- Remove the `noindex` meta tag when the site goes live.

## Deploy
GitHub Pages from `main` / root. Repo: `wilsonramstead/mjs-junk-removal`. Static,
self-contained (HTML/CSS/vanilla JS). Built by [Wilson Innovations](https://wilsoninnovations.net).
