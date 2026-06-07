## Goal

Keep the current Aurelius layout, typography, and palette exactly as approved, but replace all brand, copy, and imagery with the real TK Foreign Private Employment Agency content from your 6 slides.

## Content mapping (slide → section)

- **Slide 1 (Hero)** → Hero: "TK Foreign Private Employment Agency", tagline "Your Trusted Partner for Overseas Employment". Replace the office-tower hero image with a more relevant photo (women workers / agency portrait from slide 2). CTAs: "Hire Domestic Staff" + "Apply as a Worker".
- **Slide 2 (About Us)** → Replace "Featured Mandates" with **About Us**: TK Manpower Recruitment intro paragraph + the specialization paragraph (housemaids, cleaners, cooks, nannies, caregivers for Saudi Arabia, Kuwait, Jordan, Gulf).
- **Slide 3 (Values + Vision)** → Replace "A search defined by precision" methodology with **Our Values** (Integrity & Transparency, Professional Service, Respect for Workers, Legal & Ethical Recruitment, Commitment to Excellence) + **Our Vision** statement. Keep the dark-navy band, gold accents, numbered editorial layout.
- **Slide 4 (Destinations)** → Replace "Practice Areas" with **Our Destinations**: 3-card grid for Kuwait, Saudi Arabia, Jordan with the destination intro line above.
- **Slide 5 (Location)** → New **Our Location** section: address "Enkulal fabrika area near Police kebebe, Pawe Building, 6th floor, Addis Ababa, Ethiopia" + embedded Google Maps iframe (Addis Ababa) + "Get Directions" link.
- **Slide 6 (Contact)** → Contact section uses the real numbers: +251 911 460 406, +251 944 100 707, email tkagent2@gmail.com.
- **Trusted-by strip**: replace fake logo names with destination country labels (Saudi Arabia · Kuwait · Jordan · UAE · Qatar) so it reads as "Placements across".
- **Footer**: TK Agency identity, single office (Addis Ababa), real contact details, practices list = Housemaids / Cleaners / Cooks / Nannies / Caregivers.

## Imagery

Generate 4 new images under `src/assets/` to replace the executive-search photos:
1. Hero: warm editorial shot of African women in uniform / agency portrait setting (replaces glass tower).
2. About/Values band: candid black-and-white portrait of a domestic worker in a respectful, dignified pose (replaces mentor portrait).
3–5. Three destination cityscapes: Kuwait City skyline, Riyadh skyline, Amman citadel — portrait orientation to match the existing card aspect.

Old `hero-building.jpg` and `portrait-mentor.jpg` are deleted.

## Design system

No token changes — keep cream / navy / gold palette, Playfair Display + Inter pairing, all spacing and section rhythm exactly as built. Only the brand mark text changes from "Aurelius" to "TK Agency" (keep the small navy square mark).

## SEO / head

- Title: "TK Foreign Private Employment Agency — Overseas Employment from Ethiopia"
- Description: "TK Manpower Recruitment connects Ethiopian workers with verified employers in Saudi Arabia, Kuwait, Jordan and the Gulf. Ethical, legal, professional."
- og:title / og:description updated to match.

## Files touched

```text
src/routes/__root.tsx   meta/title/description
src/routes/index.tsx    full content swap, same layout
src/assets/             4 new images, 2 removed
```

## Out of scope (ask before adding)

- Multi-page routes for About / Location / Contact (currently all single-page sections).
- A real worker-application form or hire-staff form with backend.
- Language toggle (Amharic / Arabic / English).
- Embedded Google Map with API key vs. a simple static iframe link.
