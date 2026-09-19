# CV-CONTENT — working base for the English CV

Status: content base only (updated 19 Sep 2026). Nothing here is invented; unconfirmed items are marked `TODO(verify)` and must not appear in the final PDF until confirmed. Target: English-first, ATS-friendly, 1–2 pages, no photo/age/marital status, no skill bars, no generic objective, no empty adjectives.

Single source of truth for: `Linkedin/CV-CONTENT.md` and `dalcinho/docs/CV-CONTENT.md` (identical copies).

---

## 1. Header

**Dálcio Garcia** (full name: Dálcio Macuete Garcia — TODO(verify): which form to print)
Senior Software Developer · Full-Stack & Product Engineering
Luanda, Angola
dalciomacuetegarcia@gmail.com · linkedin.com/in/dalcio-garcia · github.com/dalcio · dalciogarcia.vercel.app

## 2. Professional summary (draft, ≤ 4 lines)

Senior software developer who builds software products from idea to production — product definition, architecture, web and mobile implementation, APIs, external integrations, deployment and operation. Founder and engineer of Pratika (POS, Mail, Domains); at Mirantes Technologies, frontend engineering and team lead on the Mirantes career platform (2022–2024), then conception and end-to-end engineering of Mirantes for Creators (2025–); application-layer Web3 integration for Interest Labs. TypeScript across the stack, React/Next.js, Flutter/React Native, Node.js/Deno, Supabase/PostgreSQL. Uses AI coding agents and LLM APIs where they add product value, keeping human ownership of architecture and quality.

## 3. Career progression (one line, optional under the summary)

Mobile Developer (2020) → Frontend / Software Engineer (2021–2022) → Frontend Developer & Frontend Team Lead (2022–2024) → Senior Software Developer (2025–) → Founder & Software Engineer (2026–)

## 4. Selected products / engineering proof

Order matches the portfolio: Pratika (own products) · Mirantes Technologies (employee work, two distinct products) · Interest Labs (freelance).

| #   | Product                                                                     | Role                                                                                                                                                                                                       | What it demonstrates                                                                                                                                                                                                               | Stack                                                                                                               | Link                    |
| --- | --------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| 01  | Pratika POS (2026)                                                          | Founder & Software Engineer — product, architecture, mobile app, backend/sync, billing workflow                                                                                                            | Offline-first mobile product with hardware integration (barcode, Bluetooth printing), local-first data model with sync, per-operator cash control, bank-transfer billing with proof-of-payment verification                        | Flutter, Dart, Next.js, Supabase, PostgreSQL, Deno                                                                  | pos.pratika.io          |
| 02  | Pratika Mail (2026 — TODO(verify): "completed" vs "final stage")            | Founder & Software Engineer — architecture, frontend, backend, provider integration, billing                                                                                                               | SaaS on top of third-party email/domain infrastructure: mailbox/alias provisioning, MX/SPF/DKIM/DMARC verification, calendar/contacts, AI assistant, 2FA/sessions, per-mailbox + storage billing, IMAP/SMTP                        | TypeScript, Next.js, Supabase, PostgreSQL, LLM APIs, third-party email infrastructure (TODO(verify): provider name) | mail.pratika.io         |
| 03  | Mirantes Platform — mirantes.io (Nov 2022 – Feb 2024)                       | Frontend Developer & Frontend Team Lead — **platform engineering, frontend only** (no backend ownership claimed)                                                                                           | Production frontend of a career/recruitment SaaS for low-bandwidth markets: Next.js/TypeScript web app, SSR/SSG strategy, React Query caching, performance and production debugging, frontend code review and technical guidance   | Next.js, TypeScript, React, React Query, Tailwind CSS                                                               | mirantes.io             |
| 04  | Mirantes for Creators (2025 – 2026 — TODO(verify): project start/end dates) | Senior Software Developer — **product engineering**: conception; led significant parts of architecture and end-to-end implementation (frontend, backend, data model, integrations, technical coordination) | Complex multi-domain platform (courses, digital products, communities, livestreams, podcast, marketplace) integrated into an existing SaaS; third-party live-streaming/management integrations; creator/product/content data model | Next.js, TypeScript, Node.js, PostgreSQL, GraphQL                                                                   | mirantesforcreators.com |
| 05  | Pratika Domains (2026)                                                      | Founder & Software Engineer — product, frontend, backend, registrar integration, billing                                                                                                                   | External API orchestration (Openprovider), domain lifecycle (search, registration, renewal, DNS, transfers), pricing/billing in Kwanza, hand-off into Mail                                                                         | Next.js, TypeScript, Supabase, PostgreSQL, Openprovider API                                                         | domains.pratika.io      |
| 06  | Winter Walrus — Interest Labs (Mar – Jul 2025, completed engagement)        | Software Engineer — Web3/DeFi applications (freelance)                                                                                                                                                     | Application-layer blockchain integration: wallet connection, transaction construction/signing, on-chain state, staking/unstaking/LST workflows against existing Move contracts (no contract authorship)                            | TypeScript, React, Sui TypeScript SDK                                                                               | winterwalrus.com        |

## 5. Experience (most recent first — same order as the portfolio)

**Pratika — Founder & Software Engineer** · Luanda (remote) · Mar 2026 – Present · Self-employed

- Built three products end-to-end (POS, Mail, Domains) — see Selected products.
- Designed the shared account, subscription and administration layer (Supabase, PostgreSQL); built bank-transfer billing with proof-of-payment verification for the Angolan market.
- Own deployment and operations of all products. (TODO(verify): hosting/cloud provider for the CV "Deployment" line)

**Mirantes Technologies — Senior Software Developer · Technology Department** · Luanda · Jan 2025 – Present · Full-time, on-site
Product: **Mirantes for Creators** (product engineering).

- Conceived and led the implementation of Mirantes for Creators: product definition, architecture and end-to-end development across frontend and backend (courses, digital products, communities, livestreams, marketplace).
- Designed and built live-experience capabilities and podcast functionality, integrating third-party live-streaming and live-management platforms. (TODO(verify): platform names, if allowed)
- Own the creator-side product infrastructure: creator accounts, content catalogue and the data model connecting creators, products and the Mirantes.io marketplace.
- Coordinate technical work within the department: technical decisions, code review and delivery planning across web and mobile codebases (Next.js, TypeScript, Node.js, PostgreSQL, GraphQL).
- Contribute to the core Mirantes platform (Next.js web app, APIs, PostgreSQL).

**Mirantes Technologies — Frontend Developer & Frontend Team Lead** · Luanda · Nov 2022 – Feb 2024 · Full-time, on-site
Product: **Mirantes Platform — mirantes.io** (platform engineering, frontend).

- Built and maintained the Next.js/TypeScript web application (SSR/SSG, lazy loading, React Query caching) for low-bandwidth performance.
- Led the frontend team's technical work: code review, technical guidance, codebase consistency.
- Owned frontend performance work and production debugging. Backend work in this period is not claimed.

**Interest Labs — Software Engineer, Web3 / DeFi Applications** · Remote · Mar 2025 – Jul 2025 · Freelance
Product: **Winter Walrus** (Web3 application).

- Application-level Web3 integrations in TypeScript/React with the Sui TypeScript SDK: wallet connection, transaction construction and signing, on-chain state in the UI.
- Staking, unstaking and LST workflows in the Winter Walrus interface; integrated existing Move contracts (no contract authorship).
- Worked remotely with a distributed team on a live product handling real user funds.

**NSDEV — Software Engineer (Frontend)** · Luanda · Sep 2021 – Oct 2022 · Full-time

- Built the React web application for T'aprovado (routing, REST API integration, main user flows); took part in UX/UI definition.

**FRN³ (via NSDEV) — Frontend Developer, VTEX** · São Paulo (remote) · Aug 2022 – Nov 2022 · Part-time

- Features, UI/UX improvements and external API integrations on VTEX IO storefronts for six-plus client stores (Babybiz, Panasonic Brazil, Portal Elétrico among them); legacy defect fixing.

**STATEMENT MC — Frontend Developer** · Luanda · Nov 2022 – Feb 2024 · TODO(verify): employment type (dates overlap Mirantes full-time)

- Frontend development of internal and client solutions (Homepro) with React/Next.js; co-tutor of a programming course for young people.

**Mochi Noir — Mobile Developer** · Lisbon (remote) · Aug 2020 – Jun 2021 · Full-time

- React Native/TypeScript mobile applications from flow design to implementation; unit and integration tests (Jest); UX/UI research.

## 6. Engineering capabilities

- **Product engineering:** product architecture, feature design, end-to-end implementation, SaaS, web and mobile applications.
- **Frontend:** React, Next.js, TypeScript, SSR/SSG, performance, caching, forms/validation, React Query, Tailwind CSS.
- **Backend:** Node.js, Deno, Supabase, PostgreSQL, GraphQL, REST API design.
- **Mobile:** Flutter, React Native, offline-first architecture, device/hardware integrations (barcode scanning, Bluetooth printing).
- **Integrations:** payment workflows, domain registrars (Openprovider), email infrastructure (MX/SPF/DKIM/DMARC), authentication & 2FA, third-party APIs, blockchain/Web3 (Sui), LLM APIs.
- **Engineering practice:** architecture, performance, security, testing, code review, deployment, debugging, technical coordination, AI-assisted development.

## 7. Education

Instituto Superior de Tecnologia e Ciências (ISPTEC), Luanda — Licenciatura (Bachelor's) in Engenharia Informática (Computer Engineering), 2017 – 2022. (TODO(verify): completion/graduation year to print)

## 8. Languages

Portuguese — native · English — professional working proficiency (TODO(verify): upgrade wording if C1/full professional)

## 9. Do-not-include list (confirmed unsupported)

80+/25+ projects · 15+ teams led · 10+/3+ products shipped · 50K+ downloads · +25% conversion · +30% performance · Ethereum · Solidity · Move contract authorship · React Native wallet "from scratch" · Clarifyne · SynthMail · "Micro-SaaS Builder" · "Indie Hacker" · "Open to Work" · Python/FastAPI/Redis/MongoDB as core stack · Machine Learning · any user/revenue numbers · backend ownership on Mirantes Platform (2022–2024).

## 10. Open TODO(verify) before generating the PDF

1. Name to print (with/without "Macuete").
2. Mirantes for Creators project dates (start / end or "ongoing").
3. Pratika Mail status wording ("completed" vs "final stage before general availability").
4. STATEMENT MC employment type/dates (overlap with Mirantes).
5. Email infrastructure provider for Pratika Mail; hosting/cloud provider for Pratika products.
6. Live-streaming platform(s) integrated in Mirantes for Creators (only if allowed to name).
7. ISPTEC graduation year; English level.
8. Availability line (remote international / relocation / contract type) — optional.
9. Portuguese CV: same structure, localise titles (Licenciatura, Luanda, Kwanza), keep technology names in English.
