# Final report — Portfolio & CV: Mirantes split, product previews, final audit (19 Sep 2026)

Scope: portfolio (`dalcinho/`) changed; GitHub README (`dalcio/README.md`) touched only for consistency; LinkedIn **not** changed. Everything is local (working tree) — no commit, no push.

## Completed

- Selected Work rebuilt as **01 Pratika POS · 02 Pratika Mail · 03 Mirantes Platform · 04 Mirantes for Creators · 05 Pratika Domains · 06 Winter Walrus**, with organisation labels inserted where the organisation changes (`PRATIKA — Product · Founder`, `MIRANTES TECHNOLOGIES — Software Engineering`, `INTEREST LABS — Freelance engineering`). Mandatory numbering kept; the group blurb is shown once.
- Real product previews for all six projects: headless-Chrome captures of the public pages (pos.pratika.io, mail.pratika.io, mirantes.io, mirantesforcreators.com, domains.pratika.io, winterwalrus.com) → `public/work/<slug>/cover.webp` (1600×1000, 24–69 KB), each with a caption "Public landing page of <host>, captured 19 Sep 2026". No generated or generic images; if a file is missing the component falls back to a typographic panel (never a fake screenshot). Capture procedure documented in `public/work/README.md`.
- Card layout: desktop text left / preview right, soft hover (1–2 px lift, no parallax/3D/video); mobile DOM order Project → Description → Role/Period → Stack → Preview → "View case study →" → "Visit product ↗".
- Hero purely typographic: "I build software products from idea to production." / "Full-stack product engineering across web, mobile, APIs and integrations." / **View my work** · **Get in touch**. Removed the "Currently / Own products / Core stack" block.
- Experience list in the required order (Pratika → Mirantes Senior → Mirantes Frontend/Team Lead → Interest Labs → NSDEV → FRN³ → STATEMENT MC → Mochi Noir), each Mirantes role mapped to its product line (`Product engineering: Mirantes for Creators`, `Platform engineering: Mirantes Platform — mirantes.io`) linking to the case study.
- Per-project OG/link previews: `app/work/[slug]/opengraph-image.tsx` renders title + kicker + role + the real capture (statically generated, 1200×630); `generateMetadata` sets title, description, canonical, `og:url`, `og:type=article`, `twitter:card=summary_large_image`.
- Quality gate: `prettier --check`, `tsc --noEmit`, `eslint` (0 errors), `next build` (21 routes, all static). Browser QA: no horizontal overflow at **320 / 375 / 390 / 414** and desktop; no console errors; 1 `h1`, no duplicate ids, all images have `alt`, every `target=_blank` link has `rel="noopener noreferrer"`; all 15 internal routes 200 (`/work/nope` → 404); all 11 external product/profile URLs 200.
- CV base updated (`Linkedin/CV-CONTENT.md` = `dalcinho/docs/CV-CONTENT.md`): Mirantes split into **Platform engineering (frontend, 2022–2024)** vs **Product engineering (Creators, 2025–)**, explicit progression line, Mirantes Platform added as product 03, do-not-include list extended with "no backend ownership on Mirantes Platform".

## Fixed

- **Mirantes mixing**: `Mirantes Platform` (Frontend Developer & Frontend Team Lead, Nov 2022 – Feb 2024, frontend claims only — case study states "Backend work in this period is not claimed") is now a separate project from `Mirantes for Creators` (Senior Software Developer, product definition/architecture/frontend/backend/data model/integrations/coordination). No duplicated experience entries.
- Creators period shown as "2025 – 2026 · project dates to confirm" instead of an invented range.
- `content/experience.ts` had array holes (stray commas) → removed.
- OG route: Satori requires `display:flex` on multi-child nodes → fixed; `<img>` lint warning suppressed with a justification (Satori only renders plain `<img>`).
- Case-study header now shows **Visit product ↗** (from `productUrl`) and the organisation kicker.

## Added

- `content/projects.ts`: `group`, `kicker`, `productUrl`, `image`, `imageAlt`, `imageSource`; `groups` record; `mirantes-platform` case study.
- `content/experience.ts`: `product { name, slug, kind }` per role.
- `public/work/{6 slugs}/cover.webp`; `assets/og/{6 slugs}.jpg` (OG-sized copies, not served publicly).
- `app/work/[slug]/opengraph-image.tsx`.
- `dalcio/README.md`: Mirantes Platform line (consistency with the portfolio).
- `docs/ARCHITECTURE.md`: imagery/OG section updated.

## Removed

- Hero CTA "Download CV" and the three-column facts block (CV still reachable from the header).
- Old flat project list and "Read case study" wording (now "View case study →").
- Nothing obsolete was found in the portfolio content: no Clarifyne, SynthMail, Indie Hacker, Micro-SaaS Builder, Open to Work, Currently Building, Coming Soon, generic Freelance, or vanity metrics (grep across `content/`, `components/`, `app/`, `docs/` — only the CV do-not-include list mentions them).

## Still missing

1. **CV PDF** — `/cv` remains a holding page (noindex). Generate from `CV-CONTENT.md` once the `TODO(verify)` items below are answered, then set `profile.cvHref`.
2. **LinkedIn** (not touched by design): no Projects entry for **Mirantes Platform**; Featured link for Creators uses `www.mirantesforcreators.com`, which returns 404 (apex works). Both should be fixed in a LinkedIn pass.
3. **Custom domain** — site still on `dalciogarcia.vercel.app`; `dalcio.dev` does not resolve.
4. GitHub profile bio (github.com settings) still says "Founder & Lead Engineer at Clarifyne AI" — outside the README.
5. Analytics — none (removed in the previous phase); add only if wanted.
6. Commit/push/deploy — not done.

## Needs my confirmation (NEEDS USER CONFIRMATION)

1. **Mirantes for Creators project dates** (start / end, or "ongoing") — currently "2025 – 2026 · project dates to confirm".
2. **Pratika Mail status** — portfolio says "2026 · Completed"; LinkedIn says "final stage before general availability"; you said you are finishing it. Which wording?
3. **Pratika POS period** — portfolio "2026 · Completed" vs LinkedIn project "Mar 2026 – Present". Product is live and maintained; do you want "2026 – Present" on the portfolio?
4. Email infrastructure provider behind Pratika Mail (name it or keep "third-party email infrastructure").
5. Live-streaming / live-management platforms integrated in Creators (only if allowed to name).
6. Hosting/cloud provider for Pratika products (for the CV "Deployment" line).
7. STATEMENT MC employment type (dates overlap the Mirantes full-time role).
8. Name form on the CV (with/without "Macuete"); ISPTEC graduation year; English level.
9. Mirantes Platform stack on the portfolio is Next.js, TypeScript, React, React Query, Tailwind CSS — confirm Tailwind was used there (React Query and Next.js are confirmed from your earlier answers).

## Coherence table

| Informação | Portfolio | LinkedIn | CV (CV-CONTENT.md) |
| --- | --- | --- | --- |
| Identity / title | Senior Software Developer · Full-Stack & Product Engineering; hero "I build software products from idea to production." | Headline "Senior Software Developer \| Full-Stack & Product Engineering \| … \| Founder, Pratika" | Same title; summary aligned |
| Pratika (company) | Founder & Software Engineer, Mar 2026 – Present, remote, Luanda | Same | Same |
| Pratika POS | 01 · 2026 · Completed · Flutter, Dart, Next.js, TS, Supabase, PostgreSQL, Deno · pos.pratika.io | Project Mar 2026 – Present, same stack | 2026, same stack — **period wording to confirm (#3)** |
| Pratika Mail | 02 · 2026 · Completed · TS, Next.js, Supabase, PostgreSQL, third-party email infra, LLM APIs · mail.pratika.io | Project 2026 – Present, "final stage" | TODO(verify) status — **#2** |
| Pratika Domains | 05 · 2026 · Completed · Next.js, TS, Supabase, PostgreSQL, Openprovider API · domains.pratika.io | Project Jun – Aug 2026, same | 2026, same — consistent |
| Mirantes Platform | 03 · Nov 2022 – Feb 2024 · Frontend Developer & Frontend Team Lead · frontend only · mirantes.io | Position exists (same title/dates); **no Projects entry; mirantes.io Featured link removed** | Row 03 + experience entry, frontend only — consistent |
| Mirantes for Creators | 04 · 2025 – 2026 (dates to confirm) · Senior Software Developer · Next.js, TS, Node.js, PostgreSQL, GraphQL · mirantesforcreators.com | Described inside the Senior position; Featured link uses **www** host (404); no Projects entry | Row 04, dates TODO(verify) — **#1** |
| Interest Labs / Winter Walrus | 06 · Mar – Jul 2025 · Freelance · TS, React, Sui TS SDK · no Move authorship | Position + Project, same | Same — consistent |
| NSDEV | Software Engineer — Frontend, Sep 2021 – Oct 2022 | Same | Same |
| FRN³ | Frontend Developer — VTEX, Aug – Nov 2022, part-time | Same | Same |
| STATEMENT MC | Frontend Developer, Nov 2022 – Feb 2024 | Same | Same + TODO(verify) type — **#7** |
| Mochi Noir | Mobile Developer, Aug 2020 – Jun 2021 | Same | Same |
| Links | LinkedIn, GitHub, dev.to, pratika.io, product URLs (apex for Creators) | Featured: pos/mail/domains + **www.mirantesforcreators.com** | Header links |

## Recommended next step

1. Answer items 1–3 above (they change visible text), then commit and push `dalcinho` (Vercel deploys) and `dalcio` (README).
2. Run a short LinkedIn pass: add a **Mirantes Platform** project (Nov 2022 – Feb 2024, associated with the Frontend Team Lead position) and re-add the Creators Featured link without `www`.
3. Generate the CV PDF from `CV-CONTENT.md` after the remaining `TODO(verify)` items, put it at `public/Dalcio-Garcia-CV.pdf`, point `profile.cvHref` to it.
