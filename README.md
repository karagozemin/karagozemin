# 👋 Welcome to My GitHub Portfolio!

Hi, I'm **Emin Karagöz** — a Web3 developer building privacy-preserving protocols, autonomous agent infrastructure, cross-chain systems, and programmable financial applications.

My work focuses on **Stellar/Soroban, confidential coordination, AI agent payments, RWA infrastructure, cross-chain execution, and verifiable autonomous systems**.

---

# 🏆 Featured Infrastructure & Protocols

### [Sub Rosa – Sealed Coordination Infrastructure on Stellar](https://github.com/karagozemin/Sub-Rosa)

A confidential coordination primitive for Stellar that enables sealed voting, auctions, grant scoring, procurement, and allocation rounds.

Participants commit encrypted decisions to a Soroban contract and lock escrow before a future Drand round. Once the reveal round arrives, commitments are opened simultaneously through publicly verifiable timelock cryptography, removing operators from the trust path.

Built as reusable infrastructure for Stellar applications, including a Soroban round contract, TypeScript SDK, timelock encryption toolkit, permissionless keeper, and integration templates.

🏆 **1st Place — Hack Privacy Track, Build On Stellar Hackathon, IBW 2026**

🛠 **Tech:** Soroban, Rust, TypeScript, Stellar, Drand, Timelock Encryption

🌐 [Live App](https://sub-rosa-web.vercel.app)

---

### [QuietBook – Confidential RWA Bookbuilding on Stellar](https://github.com/karagozemin/QuietBook)

Confidential bookbuilding infrastructure for tokenized real-world assets on Stellar.

QuietBook lets issuers collect investor bids without exposing bid prices, sizes, or balances during price discovery while keeping final allocation and settlement verifiable on-chain.

🏆 **1st Place — Stellar Builder Summit São Paulo 2026**

🛠 **Tech:** Stellar, Soroban, TypeScript, Confidential Bookbuilding, RWA Infrastructure

---

### [OverSync – ETH ⇄ XLM Cross-Chain Bridge](https://github.com/karagozemin/OverSync)

OverSync moves native assets between Ethereum and Stellar atomically.

Funds are locked in hash-time-lock contracts on both chains, with settlement triggered by a SHA-256 preimage reveal rather than multisig attestations.

If coordinators, resolvers, RPC infrastructure, or the frontend fail, funds either settle correctly or become permissionlessly refundable.

🏆 **ETHGlobal Unite Finalist**

🛠 **Tech:** Solidity, Stellar SDK, TypeScript, React, HTLC, 1inch Fusion+

🎬 [Demo Video](https://youtu.be/Ey9Psqh4YpY) · 🌐 [Live App](https://oversync.vercel.app)

---

### [0Gents – AI-Powered INFT Marketplace](https://github.com/karagozemin/0Gents-Marketplace)

A decentralized marketplace for AI-powered Intelligent NFTs built on 0G Network.

🏆 **0G Buildathon Finalist & Winner**

🛠 **Tech:** Next.js, Solidity, 0G Compute, TypeScript

🎬 [Demo Video](https://youtu.be/nIPRd8aUGBg) · 🌐 [Live App](https://0gents.shop)

---

### [AgentAllowance – Policy-Aware x402 Infrastructure for AI Agents](https://github.com/karagozemin/AgentAllowance)

Autonomous spending infrastructure that allows AI agents to transact on Stellar under enforceable wallet policies.

AgentAllowance combines delegated authorization, spending limits, recipient policies, and x402 payment flows so agents can pay for services without receiving unrestricted treasury access.

🛠 **Tech:** Stellar, Soroban, x402, Smart Accounts, TypeScript, OpenZeppelin

---

### [Agent Commerce Hub – Marketplace for Paid AI Services](https://github.com/karagozemin/Agent-Commerce-Hub)

A marketplace where AI services are discovered, called, and paid for autonomously.

Each tool invocation is paid through **GOAT Flow / x402**, while backend payment verification ensures services are fulfilled only after settlement confirmation.

🛠 **Tech:** GOAT Network, GOAT Flow, x402, TypeScript, AI Agents

---

### [Kavro Protocol – Private Credit Clearing Network for Autonomous Agents](https://github.com/karagozemin/Kavro-Protocol)

A confidential credit coordination network where issuer, investor, underwriter, auditor, and settlement agents coordinate private RWA funding rounds.

Kavro combines sealed commitments, AI underwriting, permissioned disclosure, and on-chain repayment settlement while separating public verifiability from sensitive credit intelligence.

🛠 **Tech:** Next.js, Solidity, TypeScript, 0G Storage, 0G Compute, 0G Chain

🌐 [Live App](https://kavro-protocol.vercel.app)

---

### [CloakOps – Confidential Token Distribution Layer](https://github.com/karagozemin/CloakOps)

A confidential campaign layer for token operations built on Zama FHE.

CloakOps enables contributor rewards, advisor vesting, and community distributions where allocations and metadata remain encrypted on-chain while campaign rules stay publicly verifiable.

🛠 **Tech:** Solidity, TypeScript, Next.js, Zama FHE, TokenOps

🌐 [Live App](https://cloak-ops.vercel.app)

---

### [Solvent – Zero-Knowledge Proof of Reserves on Stellar](https://github.com/karagozemin/Solvent)

A privacy-preserving proof-of-reserves system for Stellar.

Solvent allows institutions to demonstrate asset backing without publicly exposing sensitive treasury structure or account-level information.

🛠 **Tech:** Stellar, Zero-Knowledge Proofs, TypeScript

---

### [0G Forge – Terminal-Native Builder CLI](https://github.com/karagozemin/0G-Forge)

A terminal-first builder for 0G workflows with prompt-driven generation, local preview, and deployment pipelines.

🛠 **Tech:** TypeScript, Node.js, CLI

🌐 [Demo](https://0g-forge.vercel.app) · 📦 [npm](https://www.npmjs.com/package/@kaptan_web3/og-cli)

---

# 🤖 Autonomous Agents & Agent Commerce

### [ReSource – Self-Healing Buyer for Agent Services](https://github.com/karagozemin/ReSource)

An autonomous service buyer designed to recover when agent services fail.

ReSource evaluates providers, executes purchases, verifies outcomes, and searches for alternative execution paths when a service becomes unavailable or returns an unusable result.

🛠 **Tech:** TypeScript, AI Agents, Autonomous Commerce, Keeper Infrastructure

---

### [RAVEN – Real-Time Autonomous Exposure Neutralizer](https://github.com/karagozemin/RAVEN)

An event-aware autonomous market agent built to react to live football market shocks and dynamically manage exposure.

🛠 **Tech:** Python, AI Agents, Market Automation

---

### [LifeOps – Agent-Consumable Lifestyle ASP](https://github.com/karagozemin/LifeOps)

An agent-consumable service provider built for the OKX.AI ecosystem.

Paid calls settle in **USDT0 on X Layer through x402 v2 and the OKX Payments SDK**, allowing autonomous agents to purchase services programmatically.

🛠 **Tech:** Python, OKX.AI, X Layer, x402, USDT0, AI Agents

---

### [CROON RFQ – Autonomous Recurring-Demand Engine](https://github.com/karagozemin/Croon-RFQ)

A recurring-demand and request-for-quote engine for autonomous agents.

Designed for agent economies where buyers continuously generate demand and providers compete to satisfy requests programmatically.

🛠 **Tech:** Python, AI Agents, RFQ Markets, Autonomous Commerce

---

### [Assay – Autonomous Creator Intelligence Buyer](https://github.com/karagozemin/Assay)

Assay evaluates which creator information sources are worth purchasing and pays them per use through x402.

The system turns data evaluation and purchasing into a machine-native workflow.

🛠 **Tech:** TypeScript, x402, Arc, AI Agents

---

### [r402 – Proof-Bound Agent Payment Firewall](https://github.com/karagozemin/r402)

A payment firewall for MetaMask Smart Accounts that constrains autonomous agents to narrowly scoped permissions.

Each payment is bound to the exact request that authorized it, allowing child agents to operate without receiving unrestricted wallet authority.

🛠 **Tech:** TypeScript, MetaMask Smart Accounts, x402, Agent Permissions

---

### [Signet – Offline Stablecoin Payment Vouchers](https://github.com/karagozemin/Signet)

Pre-funded stablecoin vouchers that can be accepted over a local peer-to-peer mesh while offline and settled on-chain once connectivity returns.

🛠 **Tech:** TypeScript, Stablecoin Payments, P2P Networking

---

# 🔧 Open Source & Ecosystem Contributions

Beyond product development, I contribute to open-source developer tooling and ecosystem infrastructure.

* **GitHub Linguist** — contributed toward Gno language recognition
* **awesome-gno** — contributions to the Gno.land developer ecosystem
* **gno-kaptan** — evidence-backed exploration of the Gno.land builder onboarding flow
* **KeeperHub First Mile** — preflight infrastructure for evidence-backed KeeperHub workflow inputs

---

# 🌐 Connect with Me

🐦 **X / Twitter**
https://x.com/kaptan_web3

💼 **LinkedIn**
https://www.linkedin.com/in/emin-karagozz

💬 **Telegram**
https://t.me/kaptan_web3
