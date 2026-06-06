# 👋 Welcome to My GitHub Portfolio!

Hi, I'm Emin Karagoz — a Web3 developer building privacy-preserving coordination systems, cross-chain infrastructure, and agent-driven financial applications.

My work focuses on economic security, adversarial system design, confidential computation, and intelligence under uncertainty.

This is a curated collection of infrastructure, protocol, and research projects spanning Stellar, Ethereum, Sui, Zama FHE, 0G, and AI agent systems.

---

# 🏆 Featured Infrastructure & Protocols

### [Sub Rosa – Sealed Coordination Infrastructure on Stellar](https://github.com/karagozemin/Sub-Rosa)

A confidential coordination primitive for Stellar that enables sealed voting, auctions, grant scoring, procurement, and allocation rounds.

Participants commit encrypted decisions to a Soroban contract and lock escrow before a future Drand round. Once the reveal round arrives, commitments are opened simultaneously through publicly verifiable timelock cryptography, removing operators from the trust path.

Built as reusable infrastructure for Stellar applications, including a Soroban round contract, TypeScript SDK, timelock encryption toolkit, permissionless keeper, and integration templates.

🏆 1st Place — Hack Privacy Track, Build On Stellar Hackathon (IBW 2026)

🛠 Tech: Soroban, Rust, TypeScript, Stellar, Drand, Timelock Encryption

🌐 [Live App](https://sub-rosa-web.vercel.app)

---

### [OverSync – ETH ⇄ XLM Cross-Chain Bridge](https://github.com/karagozemin/OverSync-1nchFusion)

OverSync moves native assets between Ethereum and Stellar atomically. Funds are locked in hash-time-lock contracts on both chains; settlement is a sha256 preimage reveal, not a multisig attestation.

If anything in the bridge fails — coordinator down, resolver malicious, RPC rate-limited, frontend offline — funds either settle to the beneficiary or refund permissionlessly to the user.

🏆 ETHGlobal Unite Finalist

🛠 Tech: Solidity, Stellar SDK, TypeScript, React

🎬 [Demo Video](https://youtu.be/Ey9Psqh4YpY) · 🌐 [Live App](https://oversync.vercel.app)

---

### [Kavro Protocol – Private Credit Clearing Network for Autonomous Agents](https://github.com/karagozemin/Kavro-Protocol)

A confidential credit coordination network where issuer, investor, underwriter, auditor, and settlement agents coordinate private RWA funding rounds.

Kavro combines sealed commitments, AI underwriting, permissioned disclosure, and on-chain repayment settlement — separating public verifiability from sensitive credit intelligence.

🛠 Tech: Next.js, Solidity, TypeScript, 0G Storage, 0G Compute, 0G Chain

🌐 [Live App](https://kavro-protocol.vercel.app)

---

### [Obscura Finance – Confidential RWA Deal Rooms](https://github.com/karagozemin/Obscura)

A confidential funding layer for private credit and RWA issuance using encrypted sealed bids, permissioned auditor disclosure, and on-chain repayment settlement.

Built with ERC-7984 Confidential Tokens, ERC-3643 identity compliance, and ERC-7540 async vault patterns.

🛠 Tech: Solidity, Next.js, TypeScript, iExec Nox, Arbitrum

🌐 [Live App](https://obscura-pi.vercel.app)

---

### [CloakOps – Confidential Token Distribution Layer](https://github.com/karagozemin/CloakOps)

A confidential campaign layer for token operations built on Zama FHE.

CloakOps enables contributor rewards, advisor vesting, and community distributions where allocation amounts and metadata remain encrypted on-chain while campaign rules stay publicly verifiable.

🛠 Tech: Solidity, TypeScript, Next.js, Zama FHE, TokenOps

🌐 [Live App](https://cloak-ops.vercel.app)

---

### [0G Forge – Terminal-Native Builder CLI](https://github.com/karagozemin/0G-Forge)

A terminal-first builder for 0G workflows with prompt-driven generation, local preview, and deploy pipelines.

🛠 Tech: TypeScript, Node.js, CLI

🎬 [Demo](https://0g-forge.vercel.app) · 📦 [npm](https://www.npmjs.com/package/@kaptan_web3/og-cli)

---

### [0Gents – AI Powered INFT Marketplace](https://github.com/karagozemin/0Gents-Marketplace)

A decentralized marketplace for AI-powered Intelligent NFTs built on 0G Network.

🏆 0G Buildathon Finalist & Winner

🛠 Tech: Next.js, Solidity, 0G Compute, TypeScript

🎬 [Demo Video](https://youtu.be/nIPRd8aUGBg) · 🌐 [Live App](https://0gents.shop)

---

### [QEDI – On-Chain LinkTree Platform (Sui)](https://github.com/karagozemin/QEDI)

A production-ready decentralized LinkTree with zkLogin, sponsored transactions, and on-chain data ownership.

🛠 Tech: Move, React, TypeScript

🌐 [Live App](https://qedi-sui.vercel.app)

---

# 🤖 Agent Systems & Coordination

### [BLACKOUT EXCHANGE](https://github.com/karagozemin/BLACKOUT)
A deterministic coordination system for adversarial environments.

🌐 [Live App](https://blackout-delta-ashen.vercel.app)

---

### [VEIL – Multi-Agent Conflict Intelligence Layer](https://github.com/karagozemin/VEIL)
A real-time AI battleground where agents debate, contradict, and escalate before producing structured outcomes.

🌐 [Live App](https://veil-web-sooty.vercel.app)

---

### [SilentSOS – Voice AI Emergency Relay](https://github.com/karagozemin/SilentSOS)

A voice AI relay for situations where people cannot safely speak during emergencies.

🏆 ElevenHacks #10 Submission

🛠 Tech: ElevenLabs Speech Engine, Groq, Next.js, WebRTC

🌐 [Live App](https://silent-sos-navy.vercel.app)

---

### [HYDRA – Parallel AI Agent Multisig Wallet](https://github.com/karagozemin/HYDRA)
🌐 [Live App](https://hydra-1.vercel.app)

---

### [Fortexa – Agent Payment Firewall](https://github.com/karagozemin/Fortexa)
🌐 [Live App](https://fortexa-five.vercel.app)

---

### [FortiLayer – Treasury Execution Firewall](https://github.com/karagozemin/FortiLayer)
🌐 [Live App](https://forti-layer.vercel.app)

---

### [Silent – Privacy-Native Compliance Layer](https://github.com/karagozemin/Silent)
🌐 [Live App](https://silent-web-eight.vercel.app)

---

### [RIPCORD – Perpetual Risk Execution Firewall](https://github.com/karagozemin/RIPCORD)
🌐 [Live App](https://ripcord-five.vercel.app)

---

### [AEGIS Prime – Confidential RWA Risk Engine](https://github.com/karagozemin/AEGIS)
🌐 [Live App](https://aegis-web-pied.vercel.app)

---

### [AXIS – Aleo Extended Identity Score](https://github.com/karagozemin/AXIS)
🌐 [Live App](https://axis-protocol.vercel.app)

---

### [NEGO – AI Agent Negotiation Protocol](https://github.com/karagozemin/NEGO)
🌐 [Live App](https://nego-gamma.vercel.app)

---

# 🧪 Research & Experimental Infrastructure

### [EmissionShield – Bittensor Emission Firewall](https://github.com/karagozemin/EmissionShield)

### [TAU Subnet – Intelligence Under Uncertainty](https://github.com/karagozemin/TAU-Subnet)

### [Accrue – Yield → RWA Converter](https://github.com/karagozemin/Accrue)

---

# 🌐 Explorers & Visualization

### [Zerix – 0G Network Explorer](https://github.com/karagozemin/0G-project)

### [Fhelix – Zama Network Visualizer](https://github.com/karagozemin/fhelix)

### [Manix – Mantle Network Explorer](https://github.com/karagozemin/Manix)

### [Blend Sentinel](https://github.com/karagozemin/sentinel-blend)

---

# 🎯 Consumer Applications

### [Walron – Web3 Patreon on Sui](https://github.com/karagozemin/walron)

### [LYNORA – Prediction Market](https://github.com/karagozemin/LYNORA)

### [Syntra – Intelligent NFT Marketplace](https://github.com/karagozemin/Syntra)

### [Narc4s – Decentralized Raffle System](https://github.com/karagozemin/narc4s)

---

# 🌐 Connect with Me

🐦 https://x.com/kaptan_web3  
🧪 https://t.me/kaptan_web3
💼 https://www.linkedin.com/in/emin-karagozz
