# LinkedIn Reconstruction — Dálcio Garcia

**Date:** 16 Sep 2026 · **Phase:** 2 — LinkedIn Reconstruction (content for approval; nothing published)
**Inputs:** AUDIT-2026-09-16.md · pratika.io · pos.pratika.io (+ /precos) · mail.pratika.io · domains.pratika.io · mirantes.io · mirantesforcreators.com · interestlabs.io · public Winter Walrus sources · your instructions in this thread.

**How to read this document**
- `[VERIFY: …]` inside profile text = a fact you must confirm or supply before publishing. The bracket is not published; the sentence around it is written so it can be dropped cleanly if you cannot confirm.
- Nothing in the audit marked NEEDS VERIFICATION was converted into a fact. Where your instructions in this thread supplied new evidence (Pratika is your company; you conceived and implemented Mirantes for Creators; you worked on Winter Walrus), that evidence is used and labelled "direct statement" in the evidence matrix.
- Claims that cannot be published yet are collected in Section 5 and are **not** in the profile text.

---

## Source discrepancies you should know about (before approval)

1. **pratika.io vs product sites.** The company site lists *Pratika Sales* as the main product and shows *Pratika POS* as "Em breve"; it does not list Mail or Domains at all. The product sites present POS (Android APK v0.2.2-b7, 15-day trial, pricing in Kz), Mail (live, pricing) and Domains (live, pricing) as available. The profile below follows the **product sites** and describes POS/Mail/Domains as launched. **[VERIFY: are all three publicly available today? Is Pratika Sales yours too, and should it appear?]**
2. **POS offline model.** pos.pratika.io says data stays on the device and syncs when connectivity returns, and also that there is "no server dependency". The profile says "offline-first with synchronisation" and does not describe the backend/sync architecture. **[VERIFY: what exists server-side — account/subscription, sync, backups?]**
3. **Mirantes for Creators public claims** (500,000+ users, 54 countries, 2M+ Kz paid, 100+ creators, 4.9/5) are company marketing numbers. None are used as your metrics.
4. **Interest Labs / Winter Walrus.** interestlabs.io lists Winter Walrus as an Interest Labs product; public sources describe it as liquid staking for WAL on Sui (wWAL, transmute between LSTs, priority-queue unstaking). Your contribution is written at the *application/integration* level only.

---

## 1. Final English LinkedIn Profile

### 1.1 Headline (220 chars max)

```
Senior Software Developer | Full-Stack & Product Engineering | TypeScript, React, Next.js, Node.js, React Native | Founder, Pratika (POS · Mail · Domains)
```
(151 characters.) Alternative without the Pratika suffix if you prefer the exact target string: `Senior Software Developer | Full-Stack & Product Engineering | TypeScript, React, Next.js, Node.js, React Native`.

### 1.2 Location
`Luanda, Angola`

### 1.3 Banner text (if you keep a text banner)
`Dálcio Garcia — Software Engineer · Full-Stack & Mobile · Pratika POS · Pratika Mail · Mirantes for Creators`
(Recommended: replace the "Hey, I'm Dálcio / Product Builder" banner with a neutral banner or a product screenshot strip.)

### 1.4 About (≈1,900 characters; LinkedIn limit 2,600)

```
I am a senior software developer who builds digital products end-to-end: from problem and product definition through architecture, implementation, integrations, testing and deployment to production.

What I have built

• Pratika POS — an offline-first Android point-of-sale for retail, mini-markets and pharmacies in Angola: catalogue, warehouse and batch/expiry tracking, barcode checkout, cash-register control, multi-employee accounts, receipts (Bluetooth printing and digital), reports and CSV import. Founder and engineer.
• Pratika Mail — professional email on custom domains: mailbox and alias administration, domain setup with MX/SPF/DKIM/DMARC verification, calendar and contacts, an AI assistant for summaries and drafts, subscriptions and storage plans, 2FA and session management. Founder and engineer.
• Pratika Domains — domain search, registration, renewal tracking and DNS management, integrated with Pratika Mail.
• Mirantes for Creators — the creator platform of Mirantes Technologies (courses, digital products, livestreams, communities, marketplace). I was responsible for its conception and for significant parts of its architecture and end-to-end implementation.
• At Interest Labs I worked on application-level Web3 integrations for Sui-based DeFi products such as Winter Walrus.

How I work

I own the whole stack: TypeScript on both sides, React and Next.js on the web, React Native on mobile, Node.js APIs, PostgreSQL, and the integrations a real product needs — email infrastructure, domain/DNS workflows, payments and external services. I make architecture, security, performance and deployment decisions early, and I keep them simple enough for a small team to run in production.

I use AI coding agents and LLM APIs where they create real product value — to accelerate exploration, testing and delivery, and as product features (for example the assistant in Pratika Mail) — while keeping human ownership of architecture, quality and technical decisions.

What I want to work on

SaaS platforms, web and mobile products and APIs that solve concrete problems for businesses and have to survive real constraints: intermittent connectivity, local payment rails, small teams, and users who are not technical.
```

**[VERIFY before publishing the About]:** (a) "payments" in the integrations sentence — confirmed only for POS payment *methods* handled in-app (cash, TPA, transfers, credit) and subscription proof-of-transfer; if you have not integrated a payment gateway anywhere, change to "payment workflows". (b) "PostgreSQL" is confirmed for Mirantes; confirm it is also the Pratika database or replace with the real one.

### 1.5 Experience

LinkedIn groups positions under one company automatically when the company page is the same. Structure below uses that.

---

#### Mirantes Technologies — grouped (Nov 2022 – Present · 3 yrs 11 mos · Luanda, Angola)

**Position 1 — Senior Software Developer · Technology Department**
Jan 2025 – Present · Full-time · Luanda, Angola · On-site **[VERIFY: on-site / hybrid / remote]**
**[VERIFY: HR title. If the contractual title is "Research and Development Engineer", use `Senior Software Developer (R&D) · Technology Department` so the title stays truthful while the description carries the engineering weight.]**

```
Software engineering and technical coordination in the Technology Department of Mirantes Technologies, an HR and careers SaaS (job marketplace, recruitment, employee management) with web and mobile apps.

• Conceived and led the implementation of Mirantes for Creators, the company's creator platform: product definition, architecture, and end-to-end development across frontend and backend for courses, digital products, communities, livestreams and the creator marketplace.
• Designed and built live-experience capabilities (live sessions and their management tooling) and podcast functionality, integrating third-party live-streaming/management platforms into the product. [VERIFY: name the platform(s) you integrated, e.g. streaming provider]
• Own the creator-side product infrastructure: creator accounts, content catalogue and the data model that connects creators, products and the Mirantes.io marketplace. [VERIFY: confirm scope — accounts/catalogue/data model]
• Coordinate technical work within the Technology Department: technical decisions, code review and delivery planning across the platform's web and mobile codebases (Next.js, TypeScript, Node.js, PostgreSQL, GraphQL). [VERIFY: team size / what "coordination" covers]
• Contribute to the core Mirantes platform (Next.js web app, APIs, PostgreSQL) alongside the Creators work. [VERIFY: which core modules in 2025–2026]
```

**Position 2 — (decision required) "Project Manager", Jan 2024 – Present**
Recommendation: **remove this as a separate position** and fold the coordination responsibilities into Position 1 (already written above). Reason: two concurrent "Present" positions, one titled Project Manager with no description, is the single strongest signal against a senior-engineer reading. If HR requires it to remain, retitle to `Technical Coordinator · Technology Department` **[VERIFY: is this an official title? If not, do not use it]** and give it three bullets that mirror the coordination bullet above with dates Jan 2024 – Dec 2024.

**Position 3 — Frontend Developer**
Nov 2022 – Feb 2024 · Full-time · Luanda, Angola
**[VERIFY: the current LinkedIn title also says "Frontend Team Leader". Keep it only if you actually led the frontend team; if yes, title becomes `Frontend Developer & Frontend Team Lead`.]**

```
Frontend engineering on the Mirantes platform, a SaaS where professionals manage their careers and applications and companies run job postings, recruitment and hiring.

• Built and maintained the Next.js/TypeScript web application, including SSR/SSG rendering strategies, lazy loading and data-fetching/caching with React Query to keep the platform fast on low-bandwidth connections.
• Owned platform performance work: caching strategies for data retrieval, rendering optimisation and debugging of production issues.
• Implemented forms, validation and application flows with TypeScript, React Form libraries and Tailwind CSS. [VERIFY: which form library — React Hook Form?]
• Participated in code review to keep code quality and consistency across the frontend codebase, and contributed to the team's development process improvements.
```

---

#### Pratika — Founder & Software Engineer
**[VERIFY: start date] – Present · Self-employed · Luanda, Angola · Hybrid/Remote [VERIFY]**
Company page: create a LinkedIn company page "Pratika" (pratika.io) if none exists, so the position is linked and grouped.

```
Pratika builds software for small and medium businesses in Angola. I founded it and I am the engineer behind its products: product definition, architecture, frontend, backend, data model, integrations, deployment and production support.

Products

• Pratika POS (Android, React Native/TypeScript [VERIFY: stack]) — offline-first point-of-sale for retail, canteens, mini-markets and pharmacies: product catalogue with CSV import and barcode support, warehouse with stock movements, batch/expiry tracking and low-stock alerts, camera barcode checkout with discounts, returns and customer credit, cash-register opening/closing with per-operator reconciliation, employee accounts, supplier and customer records, receipts via Bluetooth printers or digital sharing, daily dashboards and period reports, and a voice assistant for registering merchandise and catalogue entries. Data is stored on the device and synchronised when connectivity returns. Subscriptions are paid by bank transfer with in-app proof-of-payment verification.

• Pratika Mail (web) — professional email on the customer's own domain: mailbox and alias provisioning, an admin panel for mailbox administration, domain connection with MX/SPF/DKIM/DMARC verification, inbox/drafts/sent/archive/spam/trash, integrated calendar and shared contacts, an AI assistant (summaries, draft suggestions, rewriting, translation, task extraction), two-factor authentication and session/activity management, subscription plans with per-mailbox and storage add-ons, and IMAP/SMTP compatibility with external clients. [VERIFY: which email infrastructure/provider sits underneath — self-hosted stack or a third-party email API?]

• Pratika Domains (web) — domain search and registration across .com/.io/.ai/.shop/.net/.org/.store/.tech, renewal tracking and notifications, DNS management and transfers, priced in Kwanza and integrated with Pratika Mail. [VERIFY: registrar/provider API integrated]

Engineering scope

• Designed the shared Pratika account system used across products for authentication, subscriptions and administration. [VERIFY: is there one shared account/billing system across POS, Mail and Domains?]
• Built the subscription and billing workflows for the Angolan market (bank transfer with manual verification, plans in Kz), rather than card-only billing. [VERIFY]
• Own deployment and operations for all three products. [VERIFY: where they run — cloud provider/hosting]
```

---

#### Interest Labs (Interest Protocol) — Software Engineer (Web3 / DeFi applications)
Mar 2025 – Jul 2025 · **[VERIFY: Contract / Part-time / Freelance]** · Remote

```
Interest Labs builds DeFi products on the Sui blockchain (DEX, liquid staking, token tooling). I worked on the application layer of its products, including Winter Walrus, a liquid-staking platform for WAL (Walrus) on Sui.

• Built application-level Web3 integrations in TypeScript/React: wallet connection, transaction construction and signing flows, and reading on-chain state into the product UI. [VERIFY: Sui TypeScript SDK / dapp-kit]
• Implemented staking, unstaking and LST (liquid staking token) workflows in the Winter Walrus interface, including real-time position and balance views. [VERIFY: which flows exactly]
• Integrated existing Move smart contracts from the product UI (contract calls, event/state reads), without authoring the contracts.
• Worked remotely with a distributed Web3 team on a live product with real user funds, with corresponding attention to transaction safety and error handling.
```
(The "React Native mobile wallet from scratch" claim from the portfolio is **not** included — see Section 5.)

---

#### NSDEV — Software Engineer
Sep 2021 – Oct 2022 · Full-time · Luanda, Angola

```
Software engineering on T'aprovado (t-aprovado.com), an Angolan platform that connects users with rated establishments.

• Built the React web application: routing (React Router), REST API integration and the main user flows.
• Took part in UX/UI definition of the product together with the team and turned it into working frontend features.
• Reviewed code and resolved frontend defects to deliver a stable product. [VERIFY: did you also work on the backend/API? If yes, add one bullet with the stack]
```

---

#### FRN³ (via NSDEV) — Frontend Developer, VTEX
Aug 2022 – Nov 2022 · Part-time · São Paulo, Brazil · Remote
**[VERIFY: was the contract with FRN³ or with NSDEV? If NSDEV, list as a second NSDEV position "Frontend Developer (VTEX) — client FRN³".]**

```
Development and maintenance of six-plus VTEX e-commerce storefronts for FRN³'s clients (including Babybiz, Panasonic Brazil store, Portal Elétrico), working remotely with a Brazilian team.

• Implemented new features and UI/UX improvements on the VTEX IO storefront framework, and integrated external APIs and services into the stores.
• Diagnosed and fixed defects in legacy storefront code across multiple stores.
• Worked in Scrum with sprint planning and reviews across a distributed team.
```

---

#### Mochi Noir — Mobile Developer
Aug 2020 – Jun 2021 · Full-time · Lisbon, Portugal · Remote

```
• Developed mobile applications in React Native and TypeScript, from application flow design to implementation. [VERIFY: app name(s); published on stores?]
• Wrote unit and integration tests (Jest) for the application and related systems.
• Contributed to UX/UI research that shaped the application flows.
```

---

#### STATEMENT MC — Frontend Developer (Nov 2022 – Feb 2024)
**Not included** until verified: the dates are identical to the Mirantes Frontend position and both are marked Full-time · On-site. If verified as a part-time/project engagement (Homepro), add a 2-bullet entry with type "Part-time" or "Freelance"; otherwise remove.

### 1.6 Projects (LinkedIn Projects section)

**Pratika POS** — pos.pratika.io · Founder & Software Engineer · [VERIFY: start] – Present · associated with: Pratika
```
Offline-first Android point-of-sale for retail, mini-markets and pharmacies in Angola. Catalogue with CSV import and barcodes, warehouse with batches/expiry and low-stock alerts, camera barcode checkout, cash-register control, employee accounts, receipts (Bluetooth/digital), reports, and a voice assistant for product entry. Role: product definition, architecture, mobile app, backend/sync and subscription workflow. Stack: React Native, TypeScript [VERIFY: backend/DB].
```

**Pratika Mail** — mail.pratika.io · Founder & Software Engineer · [VERIFY: dates] · associated with: Pratika
```
Professional email on custom domains for businesses. Mailbox/alias administration, MX/SPF/DKIM/DMARC domain verification, calendar and contacts, AI assistant (summaries, drafts, rewriting, translation, tasks), 2FA, session management, subscription plans with storage add-ons, IMAP/SMTP compatibility. Role: architecture, frontend, backend, email/domain infrastructure integration, billing. Stack: TypeScript, React/Next.js, Node.js [VERIFY: DB, email infrastructure].
```

**Pratika Domains** — domains.pratika.io · Founder & Software Engineer · [VERIFY: dates] · associated with: Pratika
```
Domain search, registration and management (.com, .io, .ai, .shop, .net, .org, .store, .tech) priced in Kwanza, with renewal tracking, DNS management and transfers, integrated with Pratika Mail. Role: product, frontend, backend, registrar integration [VERIFY: provider], billing.
```

**Winter Walrus (Interest Labs)** — winterwalrus.com · Software Engineer (application/Web3 integration) · Mar 2025 – Jul 2025 · associated with: Interest Labs
```
Liquid-staking platform for WAL on the Sui blockchain. Contributed to the application layer: wallet connection, transaction flows, staking/unstaking and LST workflows in the product UI, integrating existing Move contracts. [VERIFY: permission to list; exact scope]
```

### 1.7 Skills

**Pinned Top 5 (in this order):** TypeScript · React.js · Next.js · Node.js · React Native

**Keep / add (supporting):** JavaScript · PostgreSQL · SQL · GraphQL · REST APIs · React Query · Tailwind CSS · Jest · Software Architecture · Full-Stack Development · Mobile Application Development · Software as a Service (SaaS) · API Development · Product Development · AI/LLM Integration · Git · Performance Optimization · Code Review · Offline-First Applications [VERIFY: LinkedIn may not have this exact skill; use "Mobile Applications"] · Email Infrastructure [VERIFY: if exists] · DNS

**Remove:** Machine Learning · Vertical AI · AI Agents · Artificial Intelligence (AI) (keep only if you want it as the 20th+ skill) · Prototyping · Python (unless used in production somewhere you can name) · "Melhoria da qualidade dos serviços" · "Otimização de desempenho" (replace with "Performance Optimization") · "node js" (duplicate of Node.js) · HTML5 as a standalone skill · VTEX (optional; keep only as historical, unpinned) · "Front-End Development" (replace with Full-Stack Development)

**Re-associate skills with positions:** TypeScript/React/Next.js/Node.js/PostgreSQL → Mirantes + Pratika; React Native → Pratika + Mochi Noir; GraphQL → Mirantes; AI/LLM Integration → Pratika (Mail assistant) + Mirantes; Software Architecture, SaaS, API Development → Pratika + Mirantes.

Export the full 51-skill list (Settings → Data privacy → Get a copy of your data → Skills) before editing so nothing is lost.

### 1.8 Featured (target state; order matters)

1. Pratika POS — case study (portfolio page) — *to be produced in Phase 3; until then, a screenshot carousel PDF or the pos.pratika.io link*
2. Pratika Mail — case study — *same*
3. English CV (PDF) — *Phase 4*
4. Portfolio — dalciogarcia.vercel.app (only after Phase 3; the current site contradicts this profile)
5. Winter Walrus / Interest Labs — link or short write-up **[VERIFY: permission]**

**Interim Featured (publishable now):** pos.pratika.io · mail.pratika.io · mirantesforcreators.com (with a one-line note "Conceived and implemented the platform's architecture and core modules"). Remove: the two 2023 React articles and the mirantes.io link (the Creators link replaces it).

### 1.9 Education

- **Instituto Superior de Tecnologia e Ciências (ISPTEC)** — Licenciatura (Bachelor's degree), Engenharia Informática (Computer Engineering), 2017 – 2022. **[VERIFY: completed?]** Skills to associate: TypeScript, React, Software Architecture (remove "Desenvolvimento web").
- **Eiffel – Ndalatando (secondary school, 2013–2015):** remove. It adds nothing internationally and pushes the profile toward "student".

### 1.10 Other sections

- **Open to Work:** turn **off** (currently on, recruiters-only, with "Javascript Developer / Frontend Developer"). Remove the "Open to Opportunities" badge from the banner.
- **Connected apps:** remove HubSpot, Gamma, Replit Agent unless you use them professionally. Keep IntelliJ only if true.
- **Languages:** Portuguese (Native) · English (Professional working) **[VERIFY: upgrade to Full professional if accurate]**.
- **Recommendations:** keep the four received. Request one new recommendation focused on engineering ownership (CEO/CTO at Mirantes on Creators; a Pratika customer; Interest Labs lead).
- **Profile language:** make **English the primary** profile and Portuguese the secondary (currently the reverse). **[VERIFY: LinkedIn only allows changing the primary language via a support request or by editing; confirm you accept the secondary-profile approach.]**
- **Public URL:** keep linkedin.com/in/dalcio-garcia.

---

## 2. Final Portuguese LinkedIn Profile

Written as a senior Angolan engineer would write in Portuguese: technical terms stay in English where that is what engineers actually say (Software Engineer, Full-Stack, backend, frontend, API, deploy, SaaS).

### 2.1 Headline

```
Senior Software Developer | Full-Stack & Product Engineering | TypeScript, React, Next.js, Node.js, React Native | Fundador, Pratika (POS · Mail · Domains)
```

### 2.2 Localização
`Luanda, Angola`

### 2.3 About

```
Sou senior software developer e construo produtos digitais de ponta a ponta: do problema e da definição do produto até à arquitectura, implementação, integrações, testes, deploy e operação em produção.

O que construí

• Pratika POS — ponto de venda Android, offline-first, para retalho, mini-mercados e farmácias em Angola: catálogo, armazém com lotes e validades, checkout por código de barras, controlo de caixa, contas de funcionários, comprovativos (impressão Bluetooth e partilha digital), relatórios e importação por CSV. Fundador e engenheiro.
• Pratika Mail — email profissional com domínio próprio: administração de caixas de correio e aliases, configuração de domínio com verificação de MX/SPF/DKIM/DMARC, calendário e contactos, assistente de IA para resumos e rascunhos, subscrições e planos de armazenamento, 2FA e gestão de sessões. Fundador e engenheiro.
• Pratika Domains — pesquisa, registo e gestão de domínios com DNS e renovações, integrado com o Pratika Mail.
• Mirantes for Creators — a plataforma de criadores da Mirantes Technologies (cursos, produtos digitais, lives, comunidades, marketplace). Fui responsável pela sua concepção e por partes significativas da arquitectura e da implementação end-to-end.
• Na Interest Labs trabalhei em integrações Web3 ao nível da aplicação para produtos DeFi na Sui, como o Winter Walrus.

Como trabalho

Assumo a stack completa: TypeScript dos dois lados, React e Next.js na web, React Native no mobile, APIs em Node.js, PostgreSQL e as integrações que um produto real exige — infraestrutura de email, fluxos de domínios/DNS, pagamentos e serviços externos. Tomo cedo as decisões de arquitectura, segurança, performance e deploy, e mantenho-as simples o suficiente para uma equipa pequena operar em produção.

Uso agentes de código e APIs de LLM onde criam valor real — para acelerar exploração, testes e entrega, e como funcionalidade de produto (por exemplo, o assistente do Pratika Mail) — mantendo a responsabilidade humana pela arquitectura, qualidade e decisões técnicas.

O que quero construir

Plataformas SaaS, produtos web e mobile e APIs que resolvem problemas concretos de empresas e têm de sobreviver a restrições reais: ligação intermitente, meios de pagamento locais, equipas pequenas e utilizadores não técnicos.
```

### 2.4 Experiência

#### Mirantes Technologies (Nov 2022 – Presente · Luanda, Angola)

**Senior Software Developer · Departamento de Tecnologia** — Jan 2025 – Presente · Tempo inteiro · Luanda · Presencial [VERIFY]
```
Engenharia de software e coordenação técnica no Departamento de Tecnologia da Mirantes Technologies, um SaaS de RH e carreiras (marketplace de emprego, recrutamento, gestão de colaboradores) com aplicações web e mobile.

• Concebi e liderei a implementação do Mirantes for Creators, a plataforma de criadores da empresa: definição do produto, arquitectura e desenvolvimento end-to-end, frontend e backend, para cursos, produtos digitais, comunidades, lives e o marketplace de criadores.
• Desenhei e construí as capacidades de live (sessões ao vivo e respectiva gestão) e a funcionalidade de podcast, integrando plataformas externas de live-streaming/gestão no produto. [VERIFY: plataforma]
• Sou responsável pela infraestrutura de produto do lado do criador: contas de criador, catálogo de conteúdos e o modelo de dados que liga criadores, produtos e o marketplace Mirantes.io. [VERIFY]
• Coordeno o trabalho técnico no Departamento de Tecnologia: decisões técnicas, code review e planeamento de entregas nas bases de código web e mobile (Next.js, TypeScript, Node.js, PostgreSQL, GraphQL). [VERIFY]
• Contribuo para a plataforma principal da Mirantes (aplicação web Next.js, APIs, PostgreSQL) em paralelo com o trabalho no Creators. [VERIFY]
```

**Frontend Developer** — Nov 2022 – Fev 2024 · Tempo inteiro · Luanda
```
Engenharia de frontend na plataforma Mirantes, um SaaS onde profissionais gerem a carreira e candidaturas e empresas gerem anúncios, recrutamento e contratações.

• Construí e mantive a aplicação web em Next.js/TypeScript, incluindo estratégias de renderização SSR/SSG, lazy loading e data fetching/caching com React Query, para manter a plataforma rápida em ligações de baixa largura de banda.
• Fui responsável pelo trabalho de performance da plataforma: estratégias de cache na obtenção de dados, optimização de renderização e depuração de problemas em produção.
• Implementei formulários, validação e fluxos da aplicação com TypeScript, bibliotecas de formulários React e Tailwind CSS. [VERIFY: biblioteca]
• Participei em code review para manter qualidade e consistência no código frontend e contribuí para a melhoria dos processos de desenvolvimento da equipa.
```

#### Pratika — Fundador & Software Engineer — [VERIFY: início] – Presente · Conta própria · Luanda, Angola
```
A Pratika constrói software para pequenas e médias empresas em Angola. Fundei-a e sou o engenheiro por trás dos produtos: definição do produto, arquitectura, frontend, backend, modelo de dados, integrações, deploy e suporte em produção.

Produtos

• Pratika POS (Android, React Native/TypeScript [VERIFY]) — ponto de venda offline-first para retalho, cantinas, mini-mercados e farmácias: catálogo com importação CSV e códigos de barras, armazém com movimentos de stock, lotes/validades e alertas de stock baixo, checkout com leitura de código de barras pela câmara, descontos, devoluções e crédito a clientes, abertura/fecho de caixa com reconciliação por operador, contas de funcionários, fichas de fornecedores e clientes, comprovativos por impressora Bluetooth ou partilha digital, painel diário e relatórios por período, e um assistente de voz para registo de mercadoria e catálogo. Os dados ficam no dispositivo e são sincronizados quando a ligação volta. As subscrições são pagas por transferência bancária com verificação do comprovativo na app.

• Pratika Mail (web) — email profissional com o domínio do cliente: provisionamento de caixas de correio e aliases, painel de administração, ligação de domínio com verificação de MX/SPF/DKIM/DMARC, caixa de entrada/rascunhos/enviados/arquivo/spam/lixo, calendário integrado e contactos partilhados, assistente de IA (resumos, sugestões de rascunho, reescrita, tradução, extracção de tarefas), autenticação de dois factores e gestão de sessões/actividade, planos de subscrição com extras por caixa e armazenamento, e compatibilidade IMAP/SMTP com clientes externos. [VERIFY: infraestrutura de email]

• Pratika Domains (web) — pesquisa e registo de domínios (.com/.io/.ai/.shop/.net/.org/.store/.tech), acompanhamento de renovações e notificações, gestão de DNS e transferências, com preços em Kwanza e integração com o Pratika Mail. [VERIFY: registrar]

Âmbito de engenharia

• Desenhei o sistema de conta Pratika partilhado entre produtos para autenticação, subscrições e administração. [VERIFY]
• Construí os fluxos de subscrição e facturação para o mercado angolano (transferência bancária com verificação manual, planos em Kz), em vez de facturação exclusivamente por cartão. [VERIFY]
• Sou responsável pelo deploy e operação dos três produtos. [VERIFY: onde correm]
```

#### Interest Labs (Interest Protocol) — Software Engineer (aplicações Web3 / DeFi) — Mar 2025 – Jul 2025 · [VERIFY: tipo] · Remoto
```
A Interest Labs constrói produtos DeFi na blockchain Sui (DEX, liquid staking, ferramentas de tokens). Trabalhei na camada de aplicação dos seus produtos, incluindo o Winter Walrus, uma plataforma de liquid staking de WAL (Walrus) na Sui.

• Construí integrações Web3 ao nível da aplicação em TypeScript/React: ligação de carteiras, construção e assinatura de transacções e leitura do estado on-chain para a interface do produto. [VERIFY: Sui TypeScript SDK]
• Implementei fluxos de staking, unstaking e LST (liquid staking token) na interface do Winter Walrus, incluindo vistas de posições e saldos em tempo real. [VERIFY]
• Integrei smart contracts Move existentes a partir da interface do produto (chamadas a contratos, leitura de eventos/estado), sem ser autor dos contratos.
• Trabalhei remotamente com uma equipa Web3 distribuída num produto em produção com fundos reais de utilizadores, com a atenção correspondente à segurança das transacções e ao tratamento de erros.
```

#### NSDEV — Software Engineer — Set 2021 – Out 2022 · Tempo inteiro · Luanda
```
Engenharia de software no T'aprovado (t-aprovado.com), plataforma angolana que liga utilizadores a estabelecimentos avaliados.

• Construí a aplicação web em React: routing (React Router), integração com a API REST e os principais fluxos de utilizador.
• Participei na definição de UX/UI do produto com a equipa e transformei-a em funcionalidades de frontend.
• Fiz code review e resolvi defeitos de frontend para entregar um produto estável. [VERIFY: backend?]
```

#### FRN³ (via NSDEV) — Frontend Developer, VTEX — Ago 2022 – Nov 2022 · Part-time · São Paulo, Brasil · Remoto [VERIFY: empregador]
```
Desenvolvimento e manutenção de mais de seis lojas VTEX para clientes da FRN³ (incluindo Babybiz, loja Panasonic Brasil e Portal Elétrico), em trabalho remoto com uma equipa brasileira.

• Implementei novas funcionalidades e melhorias de UI/UX no framework de storefront VTEX IO e integrei APIs e serviços externos nas lojas.
• Diagnostiquei e corrigi defeitos em código legado de storefront em várias lojas.
• Trabalhei em Scrum, com planeamento de sprints e revisões, numa equipa distribuída.
```

#### Mochi Noir — Mobile Developer — Ago 2020 – Jun 2021 · Tempo inteiro · Lisboa, Portugal · Remoto
```
• Desenvolvi aplicações mobile em React Native e TypeScript, do desenho dos fluxos da aplicação à implementação. [VERIFY: nome da app]
• Escrevi testes unitários e de integração (Jest) para a aplicação e sistemas relacionados.
• Contribuí para a investigação de UX/UI que definiu os fluxos da aplicação.
```

### 2.5 Projectos (PT)

**Pratika POS** — pos.pratika.io
```
Ponto de venda Android, offline-first, para retalho, mini-mercados e farmácias em Angola. Catálogo com importação CSV e códigos de barras, armazém com lotes/validades e alertas de stock, checkout por câmara, controlo de caixa, contas de funcionários, comprovativos (Bluetooth/digital), relatórios e assistente de voz para registo de produtos. Papel: definição do produto, arquitectura, app mobile, backend/sincronização e fluxo de subscrição. Stack: React Native, TypeScript [VERIFY].
```
**Pratika Mail** — mail.pratika.io
```
Email profissional com domínio próprio para empresas. Administração de caixas/aliases, verificação de domínio MX/SPF/DKIM/DMARC, calendário e contactos, assistente de IA (resumos, rascunhos, reescrita, tradução, tarefas), 2FA, gestão de sessões, planos de subscrição com extras de armazenamento, compatibilidade IMAP/SMTP. Papel: arquitectura, frontend, backend, integração da infraestrutura de email/domínios, facturação. Stack: TypeScript, React/Next.js, Node.js [VERIFY].
```
**Pratika Domains** — domains.pratika.io
```
Pesquisa, registo e gestão de domínios (.com, .io, .ai, .shop, .net, .org, .store, .tech) com preços em Kwanza, acompanhamento de renovações, gestão de DNS e transferências, integrado com o Pratika Mail. Papel: produto, frontend, backend, integração com registrar [VERIFY], facturação.
```
**Winter Walrus (Interest Labs)** — winterwalrus.com
```
Plataforma de liquid staking de WAL na blockchain Sui. Contribuí na camada de aplicação: ligação de carteiras, fluxos de transacção, staking/unstaking e workflows de LST na interface, integrando contratos Move existentes. [VERIFY: permissão]
```

### 2.6 Competências (PT)
Same list as 1.7 — LinkedIn skills are language-independent entities; only pin order needs to be set once.

### 2.7 Formação (PT)
ISPTEC — Licenciatura em Engenharia Informática, 2017–2022. Remover Eiffel – Ndalatando.

---

## 3. Change Log

| # | Section | Current | New | Reason |
|---|---|---|---|---|
| 1 | Open to Work | On (recruiters only): Javascript Developer, Frontend Developer | **Off**; badge removed from banner | Contradicts senior full-stack positioning; you do not want job-seeking framing |
| 2 | Headline | Senior Software Developer \| Full-Stack & Product Engineering \| TypeScript, React, Next.js, Node.js, React Native \| AI-enabled Products | Same core + "Founder, Pratika (POS · Mail · Domains)" instead of "AI-enabled Products" | Names real products; AI becomes supporting, not identity |
| 3 | Location | Angola | Luanda, Angola | Consistency with portfolio/CV; recruiter search |
| 4 | Banner | "Hey, I'm Dálcio / Full-Stack Engineer & Product Builder / Open to Opportunities" | Neutral banner or product strip | "Product Builder" + badge read as indie/job-seeking |
| 5 | About | Good structure, no products named, no mobile specifics | Four-question structure; names Pratika POS/Mail/Domains, Mirantes for Creators, Winter Walrus; AI as supporting | Adds evidence anchors; keeps end-to-end thesis |
| 6 | Mirantes — current title | Research And Development Engineer (Jan 2025–), description about AI/ML/Python research | Senior Software Developer · Technology Department (or "(R&D)" variant if HR requires), description about Creators platform and technical coordination | Removes R&D/ML identity; reflects stated reality; keeps title truthful pending HR confirmation |
| 7 | Mirantes — Project Manager | Separate position, Jan 2024–Present, no description | Removed; coordination folded into current role (fallback: retitle to Technical Coordinator with dates ending Dec 2024) | Two concurrent "Present" titles, one PM, is the strongest anti-senior-engineer signal |
| 8 | Mirantes — Frontend | "Desenvolvedor de front-end e Frontend Team Leader", Portuguese, emojis, present-tense task list | "Frontend Developer" (Team Lead only if verified), English, system-level bullets | Removes unverified lead claim; seniority through scope |
| 9 | Pratika | Absent | New position: Founder & Software Engineer, with three products and engineering scope | Primary evidence of zero-to-production delivery |
| 10 | Interest Labs | Absent on LinkedIn; portfolio claims Ethereum, Move dev, RN wallet, Web3.js | New position, Sui/Winter Walrus, application-level integration only; no Ethereum/Solidity/Move authorship/wallet claim | Matches public sources and your instruction; removes inflation |
| 11 | STATEMENT MC | Full-time, same dates as Mirantes Frontend | Held out until verified | Identical concurrent full-time dates look like a data error |
| 12 | FRN³ | Portuguese, emojis, jokes ("Tecnologia do sofrimento"), typos | English, 3 bullets, named clients | Professional tone; keeps real international client work |
| 13 | NSDEV | Portuguese task list | English, product-named bullets | Seniority through product context |
| 14 | Mochi Noir | Portuguese | English, 3 bullets | Consistency |
| 15 | Skills top | GraphQL, Python, SQL, PostgreSQL, node js, AI Agents, Vertical AI, ML, AI, Prototyping | Pinned: TypeScript, React.js, Next.js, Node.js, React Native; ML/Vertical AI/AI Agents/Prototyping/Python removed; PT-named skills replaced | Core stack first; removes unsupported ML identity |
| 16 | Featured | Two 2023 React articles + mirantes.io | Interim: pos.pratika.io, mail.pratika.io, mirantesforcreators.com; target: case studies, CV, portfolio | Proof of products, not articles |
| 17 | Projects | Empty | POS, Mail, Domains, Winter Walrus | LinkedIn's dedicated proof section |
| 18 | Education | ISPTEC + secondary school | ISPTEC only | International norm |
| 19 | Connected apps | Gamma, IntelliJ, HubSpot, Replit Agent | Remove non-professional ones | Noise |
| 20 | Profile language | PT primary, EN secondary | EN primary, PT secondary (both rewritten) | International audience first; both versions carry the same identity |
| 21 | Removed claims | (portfolio) 80+/25+ projects, 15+ teams, 10+ products, 50K+ downloads, +25% conversion, +30% performance, Ethereum, ML, Team Lead, "Currently building Clarifyne" | Not present anywhere in the LinkedIn text | Unsupported |

---

## 4. Evidence Matrix

| Claim | Source(s) | Confidence | Published? |
|---|---|---|---|
| Pratika is your company; you are founder and the engineer behind its products | Direct statement (this thread) | High (statement) / needs company page + dates | Yes, with [VERIFY: dates] |
| Pratika POS exists, is an Android app, offline-first with sync, features as listed, subscriptions by bank transfer in Kz | pos.pratika.io + /precos | High (product scope) | Yes |
| Pratika POS is built in React Native/TypeScript | Your target-stack statement; not on the site | Medium | Yes with [VERIFY] |
| Pratika POS backend/sync architecture | None (site says data local + syncs) | Low | No — not described |
| Pratika Mail exists with mailbox/alias admin, MX/SPF/DKIM/DMARC verification, calendar, contacts, AI assistant, 2FA, plans, IMAP/SMTP | mail.pratika.io | High | Yes |
| Pratika Mail underlying email infrastructure/provider | None | Low | No — [VERIFY] |
| Pratika Domains exists: search, registration, TLD list, DNS, transfers, renewals, Kz pricing, Mail integration | domains.pratika.io | High | Yes |
| Pratika Domains registrar/provider integration | None | Low | No — [VERIFY] |
| Shared Pratika account across products | mail.pratika.io ("Pratika account for administration"), domains login; not confirmed as one system | Medium | Yes with [VERIFY] |
| POS/Mail/Domains all "live" today | Product sites yes; pratika.io says POS "Em breve", omits Mail/Domains | Medium | Yes with [VERIFY] |
| Mirantes Technologies is an HR/careers SaaS with web + mobile apps, Luanda | mirantes.io, Play Store, Tracxn, CEO posts | High | Yes |
| You conceived and implemented Mirantes for Creators (architecture, frontend, backend; courses, digital products, live, podcast, marketplace, creator infra) | Direct statement + mirantesforcreators.com (product scope) | High (statement) / Medium (exact module ownership) | Yes, with [VERIFY] on platform names and scope |
| Creators payments (Multicaixa Express, EMIS, Unitel Money, é-Kwanza, cards) integrated by you | mirantesforcreators.com lists them; no statement from you | Low | No |
| Technical coordination in Technology Department | LinkedIn About (existing) + direct statement | High | Yes, with [VERIFY: scope] |
| Senior Software Developer as current title | Direct statement of "professional reality"; HR title unknown (LinkedIn suggests R&D Engineer) | Medium | Yes, with HR-title check |
| Frontend work at Mirantes 2022–2024: Next.js, TS, React Query, SSR/SSG, caching, performance | Existing LinkedIn description | High | Yes |
| "Frontend Team Leader" | Existing LinkedIn title only | Medium | Only if you confirm |
| Interest Labs builds Sui DeFi products; Winter Walrus is one of them; WAL liquid staking (wWAL) | interestlabs.io, Everstake/Stakin/CoinGecko | High | Yes (context) |
| You worked on Winter Walrus, application-level Web3 integrations, Mar–Jul 2025, remote | Direct statement + portfolio dates | High (statement) / Medium (scope detail) | Yes, with [VERIFY] on SDK and flows |
| Employment type at Interest Labs | None | Low | Placeholder [VERIFY] |
| Ethereum / Solidity / Move authorship / RN mobile wallet | Portfolio only; contradicted or unconfirmed | Low | **No** |
| NSDEV / T'aprovado: React, React Router, REST, UX/UI, Sep 2021–Oct 2022 | Existing LinkedIn + t-aprovado.com | High | Yes |
| FRN³: 6+ VTEX stores, named clients, Aug–Nov 2022, part-time remote | Existing LinkedIn + media | High | Yes; employer entity [VERIFY] |
| Mochi Noir: React Native, TypeScript, Jest, Aug 2020–Jun 2021 | Existing LinkedIn | High | Yes |
| STATEMENT MC | Existing LinkedIn; dates collide | Low | No |
| ISPTEC Licenciatura 2017–2022 | Existing LinkedIn | High | Yes |
| PostgreSQL / GraphQL / Node.js at Mirantes | Existing LinkedIn skills + About | High | Yes |
| PostgreSQL at Pratika | None | Low | About sentence flagged |
| AI assistant in Pratika Mail (summaries, drafts, rewriting, translation, tasks) | mail.pratika.io | High | Yes |

---

## 5. Unverified claims — must NOT be published yet

1. **Any Pratika dates** (founding, POS/Mail/Domains start/launch).
2. **Pratika stack details**: React Native for POS; backend language; database; hosting/cloud; email infrastructure provider for Mail; registrar API for Domains; whether one account/billing system spans all products.
3. **POS sync/backend architecture** (site is ambiguous: local-only vs sync).
4. **Pratika Sales** — appears as the main product on pratika.io; not mentioned by you.
5. **Mirantes HR title** for the current role; whether "Project Manager" is an official position that must remain.
6. **Mirantes on-site/remote**; team size and the precise meaning of "coordination".
7. **Mirantes for Creators**: exact modules you own vs the team; the live-streaming/management platform(s) integrated; payments integration ownership.
8. **"Frontend Team Leader"** (2022–2024).
9. **Interest Labs**: employment type; exact flows implemented; Sui TypeScript SDK/dapp-kit usage; permission to name Winter Walrus publicly; NDA.
10. **React Native mobile wallet for Sui assets "from scratch"** (portfolio) — excluded until confirmed.
11. **Ethereum, Solidity, Move authorship, Web3.js** — excluded; contradicted by public sources / your instruction.
12. **STATEMENT MC** engagement (type and dates).
13. **FRN³ vs NSDEV** as legal employer for the VTEX work.
14. **Mochi Noir** app name / store publication.
15. **All numeric claims** from the portfolio (80+/25+ projects, 15+ teams, 10+ products, 50K+ downloads, +25%, +30%).
16. **Degree completion** (ISPTEC) and **English level** upgrade.
17. **PostgreSQL at Pratika** and **payment gateway integration** anywhere (vs payment *workflows*).

---

## 6. Browser Execution Plan (runs only after your approval)

**Pre-flight (you):** answer the [VERIFY] items you can; for the rest, tell me "drop" or "keep with placeholder removed". Confirm the HR title decision (#5) and the Project Manager decision (#7). Export your LinkedIn data (Settings → Data privacy → Get a copy of your data) as a backup.

**Order of operations (me, in your Chrome session, one section at a time, screenshot before/after each save):**

1. **Open to Work → off.** Profile → "Open to" → edit → remove job preferences / turn off.
2. **Banner:** upload the new banner (you supply the image) or remove the current one.
3. **Intro:** headline, location (Luanda, Angola), industry = Software Development.
4. **About:** paste English About.
5. **Experience — Mirantes:**
   a. Edit "Research And Development Engineer" → new title, dates unchanged, employment type, location type, new description, skills re-associated.
   b. "Project Manager" → delete (or retitle per your decision).
   c. "Desenvolvedor de front-end e Frontend Team Leader" → "Frontend Developer" (+ "& Frontend Team Lead" only if confirmed), English description.
6. **Experience — Pratika:** create company page if missing (Pratika, pratika.io, Software Development, Luanda, 1–10) → add position Founder & Software Engineer with dates, Self-employed, description, skills.
7. **Experience — Interest Labs:** add position (search company page "Interest Labs"/"Interest Protocol"; fall back to free-text company if no page), dates Mar–Jul 2025, employment type per your answer, Remote, description.
8. **Experience — NSDEV, FRN³, Mochi Noir:** replace descriptions with English versions; fix FRN³ employer entity if needed.
9. **Experience — STATEMENT MC:** delete or edit per your answer.
10. **Projects:** add four projects with links and associations.
11. **Skills:** delete listed removals; add missing; pin top 5 in order; re-associate with positions.
12. **Featured:** remove articles + mirantes.io link; add pos.pratika.io, mail.pratika.io, mirantesforcreators.com.
13. **Education:** delete secondary school; update ISPTEC skills.
14. **Connected apps / Interests:** remove noise.
15. **Secondary language profile (Portuguese):** switch to the PT profile and paste each PT section (headline, About, every experience description, projects). Primary-language change to English: attempt via profile-language settings; if LinkedIn blocks it, keep PT primary and ensure the EN secondary is complete (viewers with EN locale see EN).
16. **Verification pass:** log out view (incognito) of linkedin.com/in/dalcio-garcia — screenshot the public profile in EN and PT; check that no [VERIFY] text leaked, that grouped Mirantes positions render in the right order, and that Open to Work is gone.
17. **Report:** before/after screenshots + list of exactly what changed.

**Safety rules during execution:** each save is a separate confirmation in the UI; I never delete a position before the replacement text is ready; if LinkedIn shows any unexpected dialog (identity verification, terms, premium prompts) I stop and ask.

---

## Appendix — Featured/Projects link inventory
- pos.pratika.io · mail.pratika.io · domains.pratika.io · pratika.io
- mirantesforcreators.com · mirantes.io
- winterwalrus.com · interestlabs.io
- t-aprovado.com
- github.com/dalcio (bio must change from "Founder & Lead Engineer at Clarifyne AI" — outside LinkedIn scope, noted)
