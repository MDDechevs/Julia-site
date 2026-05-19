# Julia Todorova Website — Continuation Notes

Use this file as the quick handoff for future chat sessions. It intentionally keeps source info, image references, and working preferences; it does **not** track every design tweak.

## Project
- Local project: `/Users/User/.openclaw/workspace/julia-todorova-site`
- Type: Bulgarian one-page business-card / landing page for a psychologist in Sofia.
- Deployment: local only for now; do not deploy before final approval.
- Local preview:
  ```bash
  cd /Users/User/.openclaw/workspace/julia-todorova-site
  python3 -m http.server 5173
  ```
  Open: `http://localhost:5173`

## Source Links / Profiles
Use these as source material and secondary trust links:
- LinkedIn: `https://www.linkedin.com/in/julia-todorova-a5bbb656?utm_source=share_via&utm_content=profile&utm_medium=member_android`
- Superdoc: `https://superdoc.bg/lekar/dzhulia-todorova`
- RazkazhiMi: `https://razkazhimi.online/providers/a738c4ca-e749-4b33-bb38-5c99cb72d5e8`
- RazkazhiMi portrait source used during planning: `https://razkazhimi-production.s3.eu-south-2.amazonaws.com/a738c4ca-e749-4b33-bb38-5c99cb72d5e8`

## Extracted / Agreed Info
- Name: Джулия Тодорова
- Role: психолог, психотерапевт
- City: София
- Address: бул. „Витоша“ 61, София
- Phone: `0878 194 843` / `+359 878 194 843`
- Email from RazkazhiMi: `todorova.djulia@gmail.com`
- Price to show: **€40** / 78.23 лв. Do **not** use 52.50 лв.
- Hours: **09:00–20:00**, with last session starting at **19:00**.
- Sessions: live / in-person sessions should be emphasized. Sofia cabinet first.
- Audience: adults, parents, and teenagers/youth.
- Approach: psychoanalytic psychotherapy; explain in human, non-jargony language.
- Experience: use **10+ години опит** as the main trust phrasing.
- Education/credentials from sources: bachelor + master in clinical psychology at NBU; psychodrama consultant; associated member of Bulgarian Psychoanalytic Society; member of Bulgarian Psychological Society.
- Experience mentioned in sources: Center for Public Support, Military Medical Academy psychiatry, National Specialized Hospital for Hematological Diseases, independent practice.

## Image References
Current project assets:
- `assets/julia-todorova-portrait.jpg` — uploaded portrait; preferred/strong hero portrait.
- `assets/julia-todorova-razkazhimi.jpg` — RazkazhiMi portrait; secondary/about image.
- `assets/psychology-cabinet-sofia.jpg` — cabinet image; must remain horizontal/natural, not forced into a vertical crop.

Original inbound uploads from the build chat:
- Cabinet image: `/Users/User/.openclaw/media/inbound/file_49---dae0be5d-61d6-4423-9c7c-245156f658ae.jpg`
- Uploaded portrait: `/Users/User/.openclaw/media/inbound/file_50---98e6fc14-50fa-47ba-bf4f-af0771c7088a.jpg`

Image usage preference:
- Hero: strongest uploaded portrait.
- About/credentials: RazkazhiMi portrait.
- Cabinet/address section: cabinet image below/near the address copy, preserving its horizontal aspect ratio.
- SEO alt text ideas:
  - `Джулия Тодорова психолог и психотерапевт София`
  - `Психологически кабинет Джулия Тодорова бул. Витоша 61 София`
  - `Психологическа консултация в София`

## CTA / Conversion Preferences
- Primary CTA should be phone-first: **“Запазете час”** linking to `tel:+359878194843`.
- She prefers phone call as the main action.
- Superdoc and LinkedIn can appear as quiet secondary links, not primary CTAs.
- No contact form for now; avoid GDPR hassle.
- Main promise should balance SEO and real user trust, not keyword stuffing.
- Do **not** mention Superdoc reviews/rating on the site.
- Testimonials: real testimonials only if approved. For presentation, placeholders are okay but should be clearly replaceable and not fake “5-star review” style.

## Tone / UX Preferences
- Bulgarian only.
- Tone: calm, serious, warm, credible, professional; not salesy, not overly clinical.
- Target patients likely need calm, clarity, privacy, and trust.
- Design direction: warm beige/cream base, muted sage/olive, deep charcoal text, soft warm accent. Avoid clinic-blue and flashy startup feel.
- Avoid visual chaos: too many cards/boxes create stress. Prefer calm hierarchy and breathing room.
- Typography must have clear hierarchy: section titles and card titles need to be visibly stronger than body text.
- Keep mobile-first behavior strong; most visitors will likely open from phone.

## SEO Intent
Primary keyword themes:
- `психолог София`
- `психотерапевт София`
- `психолог бул. Витоша`
- `психоаналитична психотерапия София`
- `психолог тревожност София`

SEO structure to preserve:
- H1 should balance user trust + SEO, e.g. psychologist in Sofia for anxiety/stress/life difficulties.
- Local NAP consistency: name, address, phone should match across site/profiles.
- Include Google Maps/address section.
- Keep structured data/schema, Bulgarian `lang="bg"`, meta title/description, Open Graph, sitemap, robots.

## Later Local SEO / Google Business Profile
Potential Google Business Profile setup, but actual submission/verification requires Julia/Dean approval and Google account access.
Suggested GBP content:
- Business name: `Джулия Тодорова – психолог и психотерапевт`
- Primary category: `Психолог`
- Secondary category if available: `Психотерапевт` / `Консултант`
- Description: focus on individual consultations for anxiety, tension, burnout, life crises, loss, relationship difficulties; adults, parents, teenagers; cabinet at бул. „Витоша“ 61; psychoanalytic psychotherapy, confidentiality, professional ethics.
- CTA: call
- Phone: `0878 194 843`
- Address: бул. „Витоша“ 61, София
- Hours: 09:00–20:00
- Website: add after final domain
