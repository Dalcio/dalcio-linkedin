# LinkedIn Reconstruction — Execution Report (16–19 Sep 2026)

Source of published text: `LINKEDIN-FINAL-CONTENT.md`. Every change below was saved in the LinkedIn UI and verified by reloading the profile.

## Done

| # | Section | Result |
|---|---|---|
| 1 | Open to Work | Job preferences deleted; badge no longer shown to recruiters. |
| 2 | Headline (PT primary + EN secondary) | `Senior Software Developer \| Full-Stack & Product Engineering \| TypeScript, React, Next.js, Node.js, React Native \| Founder, Pratika (POS · Mail · Domains)` |
| 3 | About (PT primary + EN secondary) | Replaced. PT primary previously contained an old 2022-era text ("Desenvolvedor Frontend com 4 anos…") — now the new PT About. EN secondary = new EN About. Both verified character-by-character. |
| 4 | Mirantes — current role | Title `Senior Software Developer · Technology Department` (PT: `· Departamento de Tecnologia`), Jan 2025–Present, Full-time, On-site, new description (Creators platform, live/podcast, creator infra, technical coordination, core platform). PT + EN. Notify-network turned off before saving. |
| 5 | Mirantes — "Project Manager" | Deleted (coordination folded into current role). |
| 6 | Mirantes — Frontend | Title `Frontend Developer & Frontend Team Lead`, new description PT + EN. |
| 7 | Pratika | New position `Founder & Software Engineer` (PT: `Fundador & Software Engineer`), Mar 2026–Present, Self-employed, Luanda, Remote, full product/engineering description PT + EN (≤2,000 chars each). |
| 8 | Interest Labs | New position `Software Engineer (Web3 / DeFi applications)` (PT: `aplicações Web3 / DeFi`), Freelance, Mar–Jul 2025, Remote, Winter Walrus / Sui TypeScript SDK description PT + EN. No Ethereum/Solidity/Move-authorship/wallet claims. |
| 9 | NSDEV | `Software Engineer (Frontend)`, EN + PT descriptions (frontend only). |
| 10 | FRN³ | `Frontend Developer (VTEX)`, EN + PT, named clients, "via NSDEV". |
| 11 | STATEMENT MC | Kept; description reduced to one clean line (PT + EN). |
| 12 | Mochi Noir | `Mobile Developer`, EN + PT. |
| 13 | Experience order | Mirantes (current) reordered above Pratika so the profile card shows Mirantes.io as current company. |
| 14 | Projects (new section) | Pratika POS (Mar 2026–Present), Pratika Domains (Jun–Aug 2026), Pratika Mail (Jul 2026–Present), Winter Walrus (Mar–Jul 2025). All associated with the matching position. Descriptions in English (LinkedIn Projects have no secondary-language version). |
| 15 | Skills | 51 → 33. Removed: Python, AI Agents, Vertical AI, Machine Learning, Artificial Intelligence (AI), Prototyping, System Development, Design Thinking, Project Management, Team Management, Coaching, coach, Amazon Web Services, react js, next js, node js, API REST, UX design (PT), Acessibilidade, Solução de problemas técnicos, Melhoria da qualidade dos serviços, Otimização de desempenho, Resolução de problemas, Melhoria contínua, Gestão de Projetos Frontend, Desenvolvimento web, Desenvolvimento de front-end, HTML5, CSS, SASS, Engenharia Informática. Added: Flutter, Dart, Supabase, Deno, Software Architecture, Full-Stack Development, Mobile Application Development, Software as a Service (SaaS), API Development, Product Development, Large Language Models (LLM), REST APIs, Performance Tuning (LinkedIn has no "Performance Optimization" entity). Pinned order: **TypeScript, React.js, Next.js, Node.js, React Native**. |
| 16 | Featured | Removed the two 2023 React articles and the mirantes.io link. Added links with descriptions: pos.pratika.io, mirantesforcreators.com, mail.pratika.io, domains.pratika.io. |
| 17 | Education | Eiffel – Ndalatando deleted; ISPTEC kept. |
| 18 | Connected apps card | Dismissed. |

## Not done / needs your hand (LinkedIn-side limits)

1. **Location "Luanda, Angola"** — LinkedIn's intro form for Angola offers no city field (only country + postal code). Location stays "Angola". If you know a postal code LinkedIn accepts for Luanda, enter it and the city will appear.
2. **Featured order** — currently Domains, Mail, Creators, POS (newest first). The reorder dialog returned "Something went wrong" on LinkedIn's side twice. Ideal order: POS, Mail, Creators, Domains — drag in Featured → ⇅ when LinkedIn is stable.
3. **Primary profile language** — still Portuguese primary / English secondary. Both are fully populated with the same identity; LinkedIn serves the English version to English-locale viewers. Switching primary requires LinkedIn support.
4. **Banner image** — still the old "Hey, I'm Dálcio / Product Builder / Open to Opportunities" image. Replace it with a neutral banner or product strip (you need to supply the image).
5. **Skill ↔ position associations** for the newly added skills were set to Pratika/Mirantes where the form allowed; a few (Software Architecture, Full-Stack Development) may show only Pratika. Cosmetic.
6. **GitHub bio** still says "Founder & Lead Engineer at Clarifyne AI" (outside LinkedIn scope).

## Notes on how it was executed
- Every position edit was done with "Notify network" OFF, so no "new job" broadcasts went out.
- LinkedIn's renderer dropped keystrokes repeatedly during the session; all long texts were injected via the native value setter and then verified against the source text before saving.
- Character limits hit and resolved: PT About (2,602 → 2,579), Pratika PT description (2,441 → 1,996), Pratika EN description (2,033 → 1,981).
