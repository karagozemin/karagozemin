# Emin Karagöz

**Software Engineer | Full-Stack · Backend · Applied AI**

I build software products end to end: turning a problem into a working application, designing the data model and APIs, implementing the frontend, and shipping the system. My work spans LLM applications, developer tools, workflow automation, and financial infrastructure.

Based in İzmir, Türkiye · Open to relocation

[LinkedIn](https://www.linkedin.com/in/emin-karagozz) · [X](https://x.com/kaptan_web3) · [Selected projects below](#selected-engineering-work)

## Selected engineering work

### [Assay](https://github.com/karagozemin/Assay) — Agent workflows and decision systems
**Python · LangGraph · FastAPI · TypeScript · Node.js · SQLite · Next.js**

Built an autonomous research workflow that evaluates information sources, decides whether to buy, skip, or reuse cached results, and records the decision. The system combines a Python/LangGraph agent, a FastAPI service streaming run events over SSE, a TypeScript backend with authorization and persistent decision ledgers, and a web interface for following each run.

[Live app](https://www.assay-web.site/app) · [Source & technical details](https://github.com/karagozemin/Assay)

### [0G Forge](https://github.com/karagozemin/0G-Forge) — Developer CLI and LLM agent runtime
**TypeScript · Node.js · LLM APIs · CLI · npm**

Built a command-line tool for generating, editing, previewing and deploying applications. Implemented reusable agent-runtime components—`AgentLoop`, `ToolRegistry`, and `MemoryLayer`—with retry/skip/abort behavior and support for OpenAI-compatible inference endpoints.

[Published CLI on npm](https://www.npmjs.com/package/@kaptan_web3/og-cli) · [Source](https://github.com/karagozemin/0G-Forge)

### [Sub Rosa](https://github.com/karagozemin/Sub-Rosa) — Open-source workflow and SDK platform
**TypeScript · Rust · SDKs · Encryption · Automated testing · CI**

Founded and independently engineered a platform for confidential submissions and verifiable multi-party workflows. Built the contract and lifecycle logic, four published TypeScript packages, integration adapters, automated operations, a hosted application, and verification tools.

- **2,871 recorded npm downloads** across four packages through November 8, 2026 (downloads, not unique users).
- **702 passing JavaScript/TypeScript and Rust tests**, recorded during project verification.
- External development work accepted or listed by **Pollar, Cosmos Pay, Proofwork and OFFER HUB**; additional independent reuse by StelHacks.
- Documented **three completed testnet auctions** and one capped mainnet proof; these are technical execution evidence, not commercial transaction volume.

[Live app](https://www.sub-rosa.online/) · [SDK](https://www.npmjs.com/package/@sub-rosa/sdk) · [Implementation and evidence](https://github.com/karagozemin/Sub-Rosa)

### [OverSync](https://github.com/karagozemin/OverSync) — Event-driven backend and transaction orchestration
**TypeScript · Node.js · Express · SQLite · PostgreSQL · Docker**

Developed an event-driven coordinator with REST APIs, order state-machine guards, event listeners, persistence and health endpoints. Implemented SQLite storage and a PostgreSQL adapter, and designed failure and refund paths for operations that cross multiple systems.

[Live testnet app](https://oversync.vercel.app/) · [Coordinator](https://github.com/karagozemin/OverSync/tree/master/coordinator) · [Database code](https://github.com/karagozemin/OverSync/blob/master/coordinator/src/persistence/db.ts)

### [FIRST100](https://github.com/karagozemin/FIRST100) — Full-stack product and authenticated gateway
**TypeScript · React · Node.js · Rust · API gateway · CI**

Developed a multi-role product covering service publishers, purchasers, rights holders and auditors, alongside an authenticated service gateway, reusable SDK and end-to-end tests. The testnet evidence documents **two finalized service orders**, delivery confirmations, and a refund path; it is not presented as paying-customer traction.

[Live testnet app](https://first100-liard.vercel.app/) · [Source](https://github.com/karagozemin/FIRST100) · [Verified testnet evidence](https://github.com/karagozemin/FIRST100/blob/main/evidence/README.md)

### [Agent Commerce Hub](https://github.com/karagozemin/Agent-Commerce-Hub) — Service marketplace and API platform
**Next.js · TypeScript · PostgreSQL · REST · MCP · Payment verification**

Implemented a marketplace and machine-facing gateway for discovering and invoking paid services, including seller authentication, service registries, PostgreSQL persistence, request validation and payment-proof verification. Separates mock-mode activity from verified payment flows.

[Source & architecture](https://github.com/karagozemin/Agent-Commerce-Hub)

## Experience and open source

- **OverBlock — Co-founder / Full-Stack Software Engineer (2023–present).** Product engineering across web applications, APIs and early-stage products. [Example: QEDI](https://github.com/karagozemin/QEDI), a React/TypeScript application with Node.js APIs, authentication and privacy controls.
- **GOAT Network — Developer Advocate (2026).** Developer-facing work around APIs, agent payments and integrations.
- **Gno.land ecosystem — Developer advocacy and tooling contributions.** Tested builder onboarding end to end, documented issues and supplied reproducible examples. [Onboarding report](https://github.com/karagozemin/gno-kaptan)
- **Drips Network — Open-source maintainer.** Maintained developer-facing open-source work and technical documentation.

## Skills

| Area | Tools and technologies |
| --- | --- |
| **Languages** | TypeScript, JavaScript, Python, Rust, Solidity, SQL |
| **Frontend** | React, Next.js, Tailwind CSS, dashboard interfaces |
| **Backend & APIs** | Node.js, Express, FastAPI, REST, Server-Sent Events, MCP |
| **Databases** | SQLite, PostgreSQL (schema design and adapter implementation) |
| **Applied AI** | LangGraph, LLM API integration, tool execution, multi-step agent workflows, validation |
| **Delivery & tooling** | Docker, GitHub Actions, automated tests, npm publishing, TypeScript SDKs, Vercel, Render |

## Selected recognition

- **1st Place — Build on Stellar, Istanbul Blockchain Week 2026 (Privacy Track)** · Sub Rosa
- **1st Place — Stellar Builder Summit São Paulo 2026 (Enterprise / RWA)** · QuietBook
- **Standout Winner — Arc & Canteen Lepton Agents Hackathon** · Assay
- **Finalist — ETHGlobal Unite** · OverSync

## Education

**Atatürk University** — Computer Programming (distance learning, in progress)

---

Many more projects exist, but this page highlights work that best demonstrates product engineering, backend systems, developer tooling and applied AI. [Browse the full earlier project catalog](./README_ARCHIVE_2026-11-25.md).

*Usage numbers on this page are scoped to the source and period stated; npm downloads are not unique users, and demos or testnet activity are not counted as production customers.*
