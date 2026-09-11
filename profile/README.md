# Solana KYC/AML Compliance SDK

**GitDigital Solana** · Open-source compliance layer for Real-World Assets, regulated DeFi, and identity-gated applications on Solana.

[![Solana](https://img.shields.io/badge/Solana-Aligned-9945FF?style=for-the-badge&logo=solana&logoColor=white)](https://solana.com)
[![Token-2022](https://img.shields.io/badge/Token--2022-Transfer%20Hook-14F195?style=for-the-badge)](https://spl.solana.com/token-2022)
[![Aurora ZK](https://img.shields.io/badge/Aurora-ZK_Cryptography-7B2CBF?style=for-the-badge)](https://github.com/GitDigital-Solana/Aurora-zk-cryptography-framework)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![Security](https://img.shields.io/badge/Security-Foundational-green?style=for-the-badge)](SECURITY.md)
[![Docs](https://img.shields.io/badge/Docs-Live-orange?style=for-the-badge)](#-documentation)
[![Version](https://img.shields.io/badge/Version-2.6-informational?style=for-the-badge)](CHANGELOG.md)

<script src="https://liberapay.com/GitDigital_liberapay/widgets/button.js"></script>
<a href="https://liberapay.com/GitDigital_liberapay/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a>
<a href="https://ko-fi.com/gitdigital"><img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Buy Me a Coffee at ko-fi.com"></a>

<p align="center">
  <img src="assets/polar-checkout-qr-verified-badge.jpg" alt="Polar Checkout QR Verified" width="140">
  &nbsp;&nbsp;&nbsp;
  <img src="assets/gitdigital-autonomous-agent-economies.png" alt="GitDigital Autonomous Agent Economies" width="280">
</p>

<p align="center">
  <strong>🔐 Cryptographic Verification Banners</strong><br>
  <em>Polar Checkout QR Verified · Autonomous Agent Economies (GitDigital-aligned)</em>
</p>

---

## 🧭 Navigation

| Layer | Pages |
|-------|-------|
| **🏛️ Core** | [Home](#solana-kycaml-compliance-sdk) · [Ecosystem Overview](#-ecosystem-overview) · [Governance Model](#-governance-model) · [Tax-First Architecture](#-tax-first--compliance-first-architecture) · [Contributor Authority](#-contributor-authority) |
| **⚙️ Enforcement** | [Compliance Registry](#-compliance-registry) · [SAS / KYC](#-solana-attestation-service--kyc) · [Transfer Hooks](#-token-2022-transfer-hooks) · [TypeScript SDK](#-typescript-sdk) |
| **💳 Marketplace & RWA** | [Tiered Role-Access Marketplace](#-tiered-role-access-marketplace) · [Legal Agreements](#-legal--identity-verified-agreements) |
| **🧬 Privacy** | [Aurora ZK](#-privacy-layer) · [Tokenless Models](#-tokenless--zero-token-models) · [ZK Identity & Registry](#-zk-identity--zk-registry) · [ZK Age & FHE](#-zk-age-verification--fhe) |
| **📚 Docs & Standards** | [Documentation](#-documentation) · [Badge Catalog](#-badge-catalog) · [Templates](#-templates--standards) |
| **🧑‍💻 Authority** | [Authority Levels](#-authority-levels) · [Zero-Token Lead Teams](#-zero-token-lead-teams) |

---

## 🏷️ Badge Wall

### 🚀 Milestones
[![Architecture Complete](https://img.shields.io/badge/🧱_Architecture-Complete-success?style=flat-square)](#)
[![Spec v2.6](https://img.shields.io/badge/📘_Spec-v2.6-blue?style=flat-square)](#)
[![Compliance Ready](https://img.shields.io/badge/🛡️_Compliance-Ready-green?style=flat-square)](#)
[![Devnet Live](https://img.shields.io/badge/🚀_Devnet-Live-informational?style=flat-square)](#)
[![Mainnet Candidate](https://img.shields.io/badge/🌐_Mainnet-Candidate-purple?style=flat-square)](#)

### 🌀 Tiers
[![Concept](https://img.shields.io/badge/🌱_Concept-Passed-lightgrey?style=flat-square)](#)
[![Prototype](https://img.shields.io/badge/🔧_Prototype-Passed-yellow?style=flat-square)](#)
[![Devnet](https://img.shields.io/badge/🟦_Devnet-Active-blue?style=flat-square)](#)
[![Audit Prep](https://img.shields.io/badge/🧪_Audit_Prep-In_Progress-orange?style=flat-square)](#)
[![Mainnet](https://img.shields.io/badge/🟩_Mainnet-Candidate-brightgreen?style=flat-square)](#)
[![Ecosystem Ready](https://img.shields.io/badge/🌀_Ecosystem-Ready-purple?style=flat-square)](#)

### 🔱 Solana Signals
[![Solana Aligned](https://img.shields.io/badge/🔱_Solana-Aligned-9945FF?style=flat-square&logo=solana&logoColor=white)](#)
[![Grant Candidate](https://img.shields.io/badge/🟣_Grant-Candidate-purple?style=flat-square)](#)
[![Grant Awarded](https://img.shields.io/badge/🟪_Grant-Pending-darkpurple?style=flat-square)](#)
[![Ecosystem Integration](https://img.shields.io/badge/🔗_Ecosystem-Integration-blueviolet?style=flat-square)](#)
[![Security Ready](https://img.shields.io/badge/🛡️_Security-Ready-green?style=flat-square)](#)

### 💼 Sponsors & Readiness
[![Sponsor Ready](https://img.shields.io/badge/💼_Sponsor-Ready-success?style=flat-square)](#)
[![DD Ready](https://img.shields.io/badge/📊_DD-Ready-blue?style=flat-square)](#)
[![Enterprise Ready](https://img.shields.io/badge/🏢_Enterprise-Ready-darkblue?style=flat-square)](#)
[![Open Source](https://img.shields.io/badge/🟦_Open_Source-MIT-informational?style=flat-square)](#)

### 🏛️ Governance & Compliance
[![Governance Published](https://img.shields.io/badge/🏛️_Governance-Published-success?style=flat-square)](#)
[![Security Policy](https://img.shields.io/badge/🔐_Security_Policy-Active-green?style=flat-square)](#)
[![Audit Packet](https://img.shields.io/badge/📂_Audit_Packet-Prepared-orange?style=flat-square)](#)
[![Reviewer Ready](https://img.shields.io/badge/📝_Reviewer-Ready-blue?style=flat-square)](#)
[![Compliance dNFT](https://img.shields.io/badge/🧬_Compliance-dNFT-purple?style=flat-square)](#)

### Core Status
[![Security Foundational](https://img.shields.io/badge/Security-Foundational-brightgreen?style=flat-square)](#)
[![Last Commit](https://img.shields.io/github/last-commit/Gitdigital-products/solana-kyc-compliance-sdk?style=flat-square)](https://github.com/Gitdigital-products/solana-kyc-compliance-sdk)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![Security Scanning](https://img.shields.io/badge/Security_Scanning-Active-green?style=flat-square)](#)
[![CI Status](https://img.shields.io/badge/CI-Passing-success?style=flat-square)](#)
[![Documentation](https://img.shields.io/badge/Documentation-Complete-blue?style=flat-square)](#)
[![Governance](https://img.shields.io/badge/Governance-Active-purple?style=flat-square)](#)

---

## 📘 Summary

**GitDigital Solana** is a Solana-native KYC/AML compliance stack that enforces identity, authority, and policy **at the token level**.

It combines:

- **Token-2022** Transfer Hooks + Permanent Delegate
- **Solana Attestation Service (SAS)** for portable credentials
- A versioned **Compliance Registry**
- A **Tiered Role-Access Marketplace**
- Modern privacy primitives: **tokenless models**, **ZK Identity**, **ZK Registry**, **ZK Age**, and **FHE**
- **[Aurora ZK Cryptography Framework](https://github.com/GitDigital-Solana/Aurora-zk-cryptography-framework)** as the underlying cryptographic engine (Groth16, alt_bn128, Pedersen, ElGamal, Plonky2)

Designed for RWA issuers, regulated DeFi, identity-gated dApps, and autonomous agent economies.

> Every transfer, role grant, and access decision is auditable, authority-scoped, and optionally zero-knowledge.

---

## 🌐 Ecosystem Overview

🏷️ `Ecosystem` · `Architecture` · `Governance` · `Solana` · `RWA` · `Privacy`

### Summary
A multi-layer architecture built for clarity, continuous compliance, automation, and contributor safety.

**Core principles**
- Federated governance with dual-approval / multi-sig rules
- Tax-first and compliance-first separation of funds & identity
- Automated enforcement (Transfer Hook + Registry + SAS)
- Contributor-safe authority levels (including zero-token lead-team roles)
- Immutable audit trails
- Transparent **and** privacy-preserving paths

### Core Layers

| Layer | Responsibility |
|-------|----------------|
| **1. Governance** | Authority levels, roles, dual-approval rules, policy |
| **2. Enforcement** | Compliance Registry · Transfer Hooks · SAS · Permanent Delegate |
| **3. Marketplace & RWA** | Tiered Role-Access Marketplace · Credit patterns · Legal Agreements |
| **4. Privacy** | Tokenless models · ZK Identity / Registry / Age · FHE hybrid · **Aurora ZK** cryptographic engine |
| **5. Documentation** | Templates · Wizard · Badge Catalog · Audit packets |

---

## 🏛️ Governance Model

🏷️ `Governance` · `Authority` · `Compliance` · `Audit`

### Summary
Ensures clear boundaries, dual-founder (or Squads multi-sig + time-lock) approvals, immutable audit trails, contributor safety, and tax-/compliance-first separation.

### Components
1. **Authority Levels** — Owner · Manager · Contributor · Automation · Lead-Team (zero-token)
2. **Approval Rules** — Privileged actions require dual approval or Squads multi-sig + time-lock; agreements require identity-verified signatures
3. **Enforcement** — KYC/SAS Validator · Transfer Hook + Registry · Immutable logs

---

## 🧑‍💻 Contributor Authority

🏷️ `Authority` · `Roles` · `Governance` · `Zero-Token`

### Authority Levels

| Level | Description | Privileged Actions |
|-------|-------------|--------------------|
| **1. Owner** | Full authority | Dual-approval required |
| **2. Manager** | Operational authority, onboarding, workflow execution | Limited / approved |
| **3. Contributor** | Task-level authority | None |
| **4. Automation** | Transfer Hook, Registry, SAS Validator, API Gateway | System-enforced |
| **5. Lead-Team** | Zero-token roles (Developer / Programmer / Designer) | Role-proof gated |

### Zero-Token Lead Teams
Lead-team roles can be exercised **without holding any token**:

- Access granted purely by valid SAS attestation or ZK role proof
- Roles stored in the Compliance Registry (or ZK Registry) with capability bitmasks
- Compatible with Squads time-locks
- Ideal for pure identity-gated dApps and account-abstraction flows

| Role | Typical Capabilities | Proof Required |
|------|----------------------|----------------|
| Lead Developer | Deploy programs, update Transfer Hooks, manage Registry | Role + KYC + optional multi-sig |
| Lead Programmer | Circuits, risk engines, PRs | Role + KYC |
| Lead Designer | Marketplace UI, branding, gated content | Role + basic attestation |

---

## 🧾 Tax-First & Compliance-First Architecture

🏷️ `Tax` · `Compliance` · `Governance` · `Audit`

### Summary
Every workflow, repo, agreement, and ledger is designed to:

- Separate personal vs business finances & identity
- Maintain audit-ready documentation
- Enforce identity and authority
- Prevent accidental commingling

### Core Principles
1. **Separation of Funds & Identity** — No money or privileged action moves without documentation, approval, and Registry/ledger entry
2. **Immutable Records** — All actions logged in Loaner Ledger patterns, Agreements, Workflow/Transfer Hook logs, and Compliance Registry events
3. **Automation Enforcement** — System prevents unauthorized transfers, missing documentation, unverified identities, and policy violations

---

## ⚙️ Enforcement Layer

### Compliance Registry

🏷️ `Registry` · `On-Chain` · `Compliance` · `Authority`

Canonical on-chain (or hybrid) directory of trusted KYC providers, wallet statuses & tiers, roles & capability bitmasks, jurisdiction policies, and versioned policy templates.

- PDA-based lookups for low-latency enforcement
- Versioned entries for auditability
- Supports both clear-text and ZK (commitment / Merkle-root) variants
- Single source of truth for Transfer Hooks, marketplaces, and zero-token gates

### Solana Attestation Service + KYC

🏷️ `KYC` · `Identity` · `Security` · `SAS`

- Identity verification via real KYC providers
- Portable, reusable SAS credentials
- Signature / attestation validation
- Authority enforcement and sanctions screening
- Optional upgrade path to ZK credentials for selective disclosure

No workflow or transfer proceeds without a valid attestation.

### Token-2022 Transfer Hooks

🏷️ `Automation` · `Token-2022` · `Enforcement` · `Security`

Continuous on-chain enforcement:

- Every transfer is intercepted and validated against the Compliance Registry or a ZK proof
- Permanent Delegate enables recovery / administrative controls (via Squads + time-lock)
- Freeze Authority for temporary locks
- DefaultAccountState for controlled account initialization

---

## 💳 Tiered Role-Access Marketplace

🏷️ `Marketplace` · `Roles` · `Lending` · `Compliance`

<p align="center">
  <img src="assets/polar-checkout-qr-verified-badge.jpg" alt="Polar Checkout QR Verified" width="120">
</p>

Listings, purchases, and role grants are gated by:

- Compliance Registry status
- Tier / role checks
- Optional zero-token proofs
- **Polar MoR / verified checkout flows** (QR-driven, tax-compliant, identity-gated)

Supports both token-gated and pure credential-gated (tokenless) experiences.

> **Polar Checkout QR Verified** — Official cryptographic trust signal for autonomous commerce and verified payments.

---

## 🧬 Privacy Layer

Powered by the **[Aurora ZK Cryptography Framework](https://github.com/GitDigital-Solana/Aurora-zk-cryptography-framework)** — the cryptographic engine for zero-knowledge proofs, commitments, and on-chain verification on Solana.

### Aurora ZK (Core Cryptographic Dependency)

Aurora provides the production-grade primitives this SDK relies on:

| Aurora Capability | Used by Compliance SDK for |
|-------------------|----------------------------|
| Optimized Groth16 verifier (low CU) | On-chain verification of ZK Identity, ZK Registry membership, and ZK Age proofs |
| alt_bn128 + BLS12-381 field arithmetic | Core elliptic-curve operations for all proofs |
| Pedersen commitments & ElGamal | Confidential attributes, range proofs, selective disclosure |
| Plonky2 (experimental) | Future recursive / cheaper proofs |
| Token-2022 + ZK Compression compatibility | Native fit with Transfer Hooks and compressed state |
| Off-chain prover + on-chain notary pattern | Heavy math runs off-chain; lightweight attestation is recorded on-chain |

> Aurora is treated as a first-class sister project. This SDK does not re-implement the same cryptographic primitives.

### Tokenless (Zero-Token) Models
Access control without requiring any SPL / Token-2022 token. Users prove attributes (KYC status, age, jurisdiction, accreditation, role) via ZK credentials or SAS attestations.

### ZK Identity & ZK Registry
- Portable zero-knowledge identity credentials with selective disclosure
- Merkle-root / commitment-based registry
- Users prove membership or policy satisfaction + nullifier without revealing clear-text status
- Proofs generated and verified via Aurora

### ZK Age Verification & FHE
- Circuits that prove age ≥ threshold (or range) without revealing date of birth
- Fully Homomorphic Encryption for computation on encrypted compliance data (risk scores, attributes) — hybrid off-chain FHE + on-chain ZK proof of correct computation (Aurora + FHE layer)

Compliance remains foundational whether the path is clear-text or zero-knowledge.

---

## 🚀 Quick Start

```bash
# Clone
git clone https://github.com/Gitdigital-products/solana-kyc-compliance-sdk.git
cd solana-kyc-compliance-sdk

# Build Rust program
cd programs/compliance_registry
cargo build-bpf

# Build TypeScript SDK
cd ../../sdk/typescript
npm install && npm run build
```

### Minimal Client Example

```typescript
import { ComplianceClient } from "@gitdigital/solana-kyc-sdk";

const client = new ComplianceClient({
  connection,
  registryProgramId,
});

// Check wallet status
const status = await client.getWalletStatus(wallet.publicKey);

if (!status.isCompliant) {
  throw new Error("Wallet not registered or attestation expired");
}
```

---

## 🛠️ Preferred Stack & Multi-Language Support

🏷️ `Performance` · `Security` · `Polyglot` · `MLOps`

On-chain programs stay in **Rust + Anchor** (Token-2022, Transfer Hooks, Registry).  
Off-chain risk engines, FHE kernels, secure gateways, oracle adapters, and agent runtimes use the languages below for speed, safety, and lower operational cost.

| Language | Primary Strengths | How it helps this SDK |
|----------|-------------------|-----------------------|
| **TypeScript** | Ubiquitous Solana client ecosystem, strong typing, excellent DX | Primary client SDK, dApp front-ends, Registry/SAS orchestration, type-safe policy engines |
| **Julia** | Extreme numerical / scientific performance (LLVM), excellent for ML & Monte-Carlo | Off-chain AML risk engines, continuous scoring, portfolio/jurisdiction risk aggregation, scientific ZK parameter tuning |
| **Mojo** | Python-like ergonomics + C++/Rust-level speed, MLIR-based, SIMD/GPU targeting | High-throughput FHE kernels, confidential risk scoring, AI-augmented sanctions screening, deterministic financial compute |
| **Ballerina** | Cloud-native, integration-first, first-class security (mTLS, JWT, OAuth2) | Secure API gateways between KYC providers ↔ SAS ↔ Compliance Registry, Travel-Rule messaging, oracle ingestion |
| **V** | Extremely fast compilation & runtime, memory-safe by default, tiny binaries | Fast off-chain verifiers, lightweight client-side tooling, high-frequency status polling against the Registry |
| **Zig** | Manual memory control + strong safety, excellent C interop, no hidden control flow | Low-level FHE primitives, BPF-adjacent tooling, high-assurance crypto helpers, performance-critical side services |
| **Nim** | Python-like productivity + C-level performance, powerful metaprogramming | Rapid development of secure services, policy engines, oracle adapters, internal tooling |
| **Crystal** | Ruby-like syntax with static typing and high performance, built-in concurrency | Rapid development of secure microservices, internal admin tools, and lightweight compliance helpers |
| **Kotlin** | Strong static typing, null safety, coroutines, excellent JVM interop | Secure microservices, enterprise KYC/AML integration, concurrent Registry/oracle handling, multiplatform wallet logic |
| **OCaml / Reason** | Extremely strong static type system, excellent for formal reasoning and high-assurance code | High-assurance compliance logic, policy decision points, formal verification of critical off-chain components, audit-friendly modules |
| **F#** | Discriminated unions, immutable records, active patterns, strong .NET interop | Compliance domain modeling (“illegal states unrepresentable”), KYC/AML decision logic, audit-friendly event sourcing, enterprise .NET integration |
| **Carbon** *(experimental)* | C++ successor with better safety & modern generics | Future systems-level components that interoperate with existing C/C++ crypto or FHE libraries |

**Guidance**
- Keep **on-chain** code in Rust + Anchor.
- Use **TypeScript** as the primary client and orchestration language.
- Use **[Aurora ZK](https://github.com/GitDigital-Solana/Aurora-zk-cryptography-framework)** for all zero-knowledge proof generation and on-chain verification primitives.
- Prefer the languages above for off-chain risk engines, FHE nodes, secure gateways, and high-assurance modules.
- Languages that reduce attack surface (Ballerina’s built-in security, V/Zig immutability & bounds checks, Mojo ownership, OCaml/F# strong type systems) and lower cost (faster runtimes → fewer machines) are preferred.
- A top-level **Makefile** unifies polyglot builds (Rust + TS + Julia/Mojo/Zig/Crystal/Kotlin/OCaml/F#/etc.).

These languages make the compliance engines, risk scoring, FHE computations, and autonomous agent loops **faster, cheaper, and more secure**.

### Planned `/lang` Directory Structure

Language-specific interop lives inside the main repository for now (clean extraction into dedicated repos later if needed):

```text
lang/
├── julia/          # AML risk engines, Monte-Carlo scoring, ZK parameter tuning
├── mojo/           # FHE kernels, confidential risk scoring, sanctions screening
├── v/              # Fast off-chain verifiers, lightweight tooling
├── zig/            # Low-level FHE primitives, high-assurance crypto helpers
├── ballerina/      # Secure API gateways, Travel-Rule, oracle ingestion
├── nim/            # Policy engines, oracle adapters, internal services
├── crystal/        # Secure microservices, admin tools, lightweight compliance helpers
├── kotlin/         # Secure microservices, enterprise KYC/AML integration
├── ocaml/          # High-assurance compliance logic, formal verification, audit-friendly modules
├── fsharp/         # Compliance domain modeling, KYC/AML decision logic, event sourcing
└── README.md       # Interop contracts, FFI/gRPC boundaries, build notes
```

Each language folder will contain:
- Thin interop wrappers (calling the core Registry / SAS / Transfer Hook surface)
- Minimal examples
- Build instructions
- Clear interface documentation

This keeps the core focused while making the polyglot surface easy to discover and later extract.

---

## 📜 Legal & Identity-Verified Agreements

🏷️ `Agreements` · `Identity` · `Compliance`

All agreements are:

- Legally binding
- Identity-verified (SAS or ZK)
- Signature-required
- Immutable

**Types**
1. Founder / Loan Agreements — dual-signature, KYC-verified
2. Contributor Agreements — role-based, authority-scoped
3. Operational / Marketplace Agreements — workflow-generated

---

## 🛡️ Security & Error Handling

All programs and clients return structured, human-readable errors. Never emit bare numeric codes.

| Code | Meaning |
|------|---------|
| `NOT_REGISTERED` | Wallet not in Compliance Registry |
| `MISSING_OR_EXPIRED_KYC` | Attestation missing or expired |
| `SANCTIONED` | Wallet on restricted list |
| `MISSING_LEAD_ROLE` | Required lead-team role not present |
| `ZERO_TOKEN_ROLE_PROOF_FAILED` | Zero-token role proof failed |
| `INVALID_ZK_PROOF` | ZK verification or nullifier failure |
| `UNDER_AGE` | Age circuit failed |
| `POLICY_VIOLATION` | Transfer Hook rejected |
| `MULTISIG_REQUIRED` | Privileged action needs Squads + time-lock |
| `FHE_ERROR` | FHE ciphertext or key issue |

---

## 📚 Documentation & Standards

🏷️ `Docs` · `Templates` · `Standards`

- **Documentation Wizard** — automates README generation, agreement templates, ledger/Registry patterns, onboarding docs, and badge walls
- **Templates Library** — reusable modules for agreements, READMEs, workflows, and contributor onboarding
- **Badge Catalog** — official GitDigital Solana badges across Governance, Automation, Lending/RWA, Documentation, Privacy, Solana Signals, and Readiness

### Related References
- **[Aurora ZK Cryptography Framework](https://github.com/GitDigital-Solana/Aurora-zk-cryptography-framework)** — Core cryptographic engine (Groth16, alt_bn128, Pedersen, ElGamal, Plonky2)
- [Compliance Registry Design](references/compliance-registry.md)
- [Tiered Marketplace](references/tiered-marketplace.md)
- [Privacy / ZK / FHE](references/privacy-zk-fhe.md)
- [Zero-Token Lead Teams](references/zero-token-lead-teams.md)
- [Solana Ecosystem Submission](docs/SOLANA-ECOSYSTEM-SUBMISSION.md)
- [Demo Design](docs/DEMO-DESIGN.md)
- [ZK Identity Architecture](docs/ZK-IDENTITY-ARCHITECTURE.md)

---

## 🏷️ Badge Catalog

| Category | Examples |
|----------|----------|
| Governance | Governance · Authority · Compliance |
| Enforcement | Registry · Transfer Hook · SAS · KYC |
| Marketplace / RWA | Credit Authority · Loaner Ledger · Marketplace |
| Privacy | ZK · FHE · Tokenless · Selective Disclosure · Aurora ZK |
| Documentation | Docs · Templates · Wizard · Badge Catalog |
| Solana Signals | Solana Aligned · Grant Candidate · Security Ready |
| Readiness | Sponsor Ready · DD Ready · Enterprise Ready |

---

## 💼 Support

<script src="https://liberapay.com/GitDigital_liberapay/widgets/button.js"></script>
<a href="https://liberapay.com/GitDigital_liberapay/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a>
<a href="https://ko-fi.com/gitdigital"><img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Buy Me a Coffee at ko-fi.com"></a>

---

## 🧾 License & Ownership

**Author & Code Owner:** Rickcreator87 (@Rickcreator87)

Licensed under the **MIT License**.  
See `LICENSE`, `CODEOWNERS`, and `AUTHORS.md`.

---

**GitDigital Solana** — Compliance that lives on-chain.  
Transparent when you need it. Zero-knowledge when you require it.
# Solana KYC/AML Compliance SDK

**GitDigital Solana** · Open-source compliance layer for Real-World Assets, regulated DeFi, and identity-gated applications on Solana.

[![Solana](https://img.shields.io/badge/Solana-Aligned-9945FF?style=for-the-badge&logo=solana&logoColor=white)](https://solana.com)
[![Token-2022](https://img.shields.io/badge/Token--2022-Transfer%20Hook-14F195?style=for-the-badge)](https://spl.solana.com/token-2022)
[![Aurora ZK](https://img.shields.io/badge/Aurora-ZK_Cryptography-7B2CBF?style=for-the-badge)](https://github.com/GitDigital-Solana/Aurora-zk-cryptography-framework)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![Security](https://img.shields.io/badge/Security-Foundational-green?style=for-the-badge)](SECURITY.md)
[![Docs](https://img.shields.io/badge/Docs-Live-orange?style=for-the-badge)](#-documentation)
[![Version](https://img.shields.io/badge/Version-2.6-informational?style=for-the-badge)](CHANGELOG.md)

<script src="https://liberapay.com/GitDigital_liberapay/widgets/button.js"></script>
<a href="https://liberapay.com/GitDigital_liberapay/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a>
<a href="https://ko-fi.com/gitdigital"><img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Buy Me a Coffee at ko-fi.com"></a>

<p align="center">
  <img src="assets/polar-checkout-qr-verified-badge.jpg" alt="Polar Checkout QR Verified" width="140">
  &nbsp;&nbsp;&nbsp;
  <img src="assets/gitdigital-autonomous-agent-economies.png" alt="GitDigital Autonomous Agent Economies" width="280">
</p>

<p align="center">
  <strong>🔐 Cryptographic Verification Banners</strong><br>
  <em>Polar Checkout QR Verified · Autonomous Agent Economies (GitDigital-aligned)</em>
</p>

---

## 🧭 Navigation

| Layer | Pages |
|-------|-------|
| **🏛️ Core** | [Home](#solana-kycaml-compliance-sdk) · [Ecosystem Overview](#-ecosystem-overview) · [Governance Model](#-governance-model) · [Tax-First Architecture](#-tax-first--compliance-first-architecture) · [Contributor Authority](#-contributor-authority) |
| **⚙️ Enforcement** | [Compliance Registry](#-compliance-registry) · [SAS / KYC](#-solana-attestation-service--kyc) · [Transfer Hooks](#-token-2022-transfer-hooks) · [TypeScript SDK](#-typescript-sdk) |
| **💳 Marketplace & RWA** | [Tiered Role-Access Marketplace](#-tiered-role-access-marketplace) · [Legal Agreements](#-legal--identity-verified-agreements) |
| **🧬 Privacy** | [Aurora ZK](#-privacy-layer) · [Tokenless Models](#-tokenless--zero-token-models) · [ZK Identity & Registry](#-zk-identity--zk-registry) · [ZK Age & FHE](#-zk-age-verification--fhe) |
| **📚 Docs & Standards** | [Documentation](#-documentation) · [Badge Catalog](#-badge-catalog) · [Templates](#-templates--standards) |
| **🧑‍💻 Authority** | [Authority Levels](#-authority-levels) · [Zero-Token Lead Teams](#-zero-token-lead-teams) |

---

## 🏷️ Badge Wall

### 🚀 Milestones
[![Architecture Complete](https://img.shields.io/badge/🧱_Architecture-Complete-success?style=flat-square)](#)
[![Spec v2.6](https://img.shields.io/badge/📘_Spec-v2.6-blue?style=flat-square)](#)
[![Compliance Ready](https://img.shields.io/badge/🛡️_Compliance-Ready-green?style=flat-square)](#)
[![Devnet Live](https://img.shields.io/badge/🚀_Devnet-Live-informational?style=flat-square)](#)
[![Mainnet Candidate](https://img.shields.io/badge/🌐_Mainnet-Candidate-purple?style=flat-square)](#)

### 🌀 Tiers
[![Concept](https://img.shields.io/badge/🌱_Concept-Passed-lightgrey?style=flat-square)](#)
[![Prototype](https://img.shields.io/badge/🔧_Prototype-Passed-yellow?style=flat-square)](#)
[![Devnet](https://img.shields.io/badge/🟦_Devnet-Active-blue?style=flat-square)](#)
[![Audit Prep](https://img.shields.io/badge/🧪_Audit_Prep-In_Progress-orange?style=flat-square)](#)
[![Mainnet](https://img.shields.io/badge/🟩_Mainnet-Candidate-brightgreen?style=flat-square)](#)
[![Ecosystem Ready](https://img.shields.io/badge/🌀_Ecosystem-Ready-purple?style=flat-square)](#)

### 🔱 Solana Signals
[![Solana Aligned](https://img.shields.io/badge/🔱_Solana-Aligned-9945FF?style=flat-square&logo=solana&logoColor=white)](#)
[![Grant Candidate](https://img.shields.io/badge/🟣_Grant-Candidate-purple?style=flat-square)](#)
[![Grant Awarded](https://img.shields.io/badge/🟪_Grant-Pending-darkpurple?style=flat-square)](#)
[![Ecosystem Integration](https://img.shields.io/badge/🔗_Ecosystem-Integration-blueviolet?style=flat-square)](#)
[![Security Ready](https://img.shields.io/badge/🛡️_Security-Ready-green?style=flat-square)](#)

### 💼 Sponsors & Readiness
[![Sponsor Ready](https://img.shields.io/badge/💼_Sponsor-Ready-success?style=flat-square)](#)
[![DD Ready](https://img.shields.io/badge/📊_DD-Ready-blue?style=flat-square)](#)
[![Enterprise Ready](https://img.shields.io/badge/🏢_Enterprise-Ready-darkblue?style=flat-square)](#)
[![Open Source](https://img.shields.io/badge/🟦_Open_Source-MIT-informational?style=flat-square)](#)

### 🏛️ Governance & Compliance
[![Governance Published](https://img.shields.io/badge/🏛️_Governance-Published-success?style=flat-square)](#)
[![Security Policy](https://img.shields.io/badge/🔐_Security_Policy-Active-green?style=flat-square)](#)
[![Audit Packet](https://img.shields.io/badge/📂_Audit_Packet-Prepared-orange?style=flat-square)](#)
[![Reviewer Ready](https://img.shields.io/badge/📝_Reviewer-Ready-blue?style=flat-square)](#)
[![Compliance dNFT](https://img.shields.io/badge/🧬_Compliance-dNFT-purple?style=flat-square)](#)

### Core Status
[![Security Foundational](https://img.shields.io/badge/Security-Foundational-brightgreen?style=flat-square)](#)
[![Last Commit](https://img.shields.io/github/last-commit/Gitdigital-products/solana-kyc-compliance-sdk?style=flat-square)](https://github.com/Gitdigital-products/solana-kyc-compliance-sdk)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![Security Scanning](https://img.shields.io/badge/Security_Scanning-Active-green?style=flat-square)](#)
[![CI Status](https://img.shields.io/badge/CI-Passing-success?style=flat-square)](#)
[![Documentation](https://img.shields.io/badge/Documentation-Complete-blue?style=flat-square)](#)
[![Governance](https://img.shields.io/badge/Governance-Active-purple?style=flat-square)](#)

---

## 📘 Summary

**GitDigital Solana** is a Solana-native KYC/AML compliance stack that enforces identity, authority, and policy **at the token level**.

It combines:

- **Token-2022** Transfer Hooks + Permanent Delegate
- **Solana Attestation Service (SAS)** for portable credentials
- A versioned **Compliance Registry**
- A **Tiered Role-Access Marketplace**
- Modern privacy primitives: **tokenless models**, **ZK Identity**, **ZK Registry**, **ZK Age**, and **FHE**
- **[Aurora ZK Cryptography Framework](https://github.com/GitDigital-Solana/Aurora-zk-cryptography-framework)** as the underlying cryptographic engine (Groth16, alt_bn128, Pedersen, ElGamal, Plonky2)

Designed for RWA issuers, regulated DeFi, identity-gated dApps, and autonomous agent economies.

> Every transfer, role grant, and access decision is auditable, authority-scoped, and optionally zero-knowledge.

---

## 🌐 Ecosystem Overview

🏷️ `Ecosystem` · `Architecture` · `Governance` · `Solana` · `RWA` · `Privacy`

### Summary
A multi-layer architecture built for clarity, continuous compliance, automation, and contributor safety.

**Core principles**
- Federated governance with dual-approval / multi-sig rules
- Tax-first and compliance-first separation of funds & identity
- Automated enforcement (Transfer Hook + Registry + SAS)
- Contributor-safe authority levels (including zero-token lead-team roles)
- Immutable audit trails
- Transparent **and** privacy-preserving paths

### Core Layers

| Layer | Responsibility |
|-------|----------------|
| **1. Governance** | Authority levels, roles, dual-approval rules, policy |
| **2. Enforcement** | Compliance Registry · Transfer Hooks · SAS · Permanent Delegate |
| **3. Marketplace & RWA** | Tiered Role-Access Marketplace · Credit patterns · Legal Agreements |
| **4. Privacy** | Tokenless models · ZK Identity / Registry / Age · FHE hybrid · **Aurora ZK** cryptographic engine |
| **5. Documentation** | Templates · Wizard · Badge Catalog · Audit packets |

---

## 🏛️ Governance Model

🏷️ `Governance` · `Authority` · `Compliance` · `Audit`

### Summary
Ensures clear boundaries, dual-founder (or Squads multi-sig + time-lock) approvals, immutable audit trails, contributor safety, and tax-/compliance-first separation.

### Components
1. **Authority Levels** — Owner · Manager · Contributor · Automation · Lead-Team (zero-token)
2. **Approval Rules** — Privileged actions require dual approval or Squads multi-sig + time-lock; agreements require identity-verified signatures
3. **Enforcement** — KYC/SAS Validator · Transfer Hook + Registry · Immutable logs

---

## 🧑‍💻 Contributor Authority

🏷️ `Authority` · `Roles` · `Governance` · `Zero-Token`

### Authority Levels

| Level | Description | Privileged Actions |
|-------|-------------|--------------------|
| **1. Owner** | Full authority | Dual-approval required |
| **2. Manager** | Operational authority, onboarding, workflow execution | Limited / approved |
| **3. Contributor** | Task-level authority | None |
| **4. Automation** | Transfer Hook, Registry, SAS Validator, API Gateway | System-enforced |
| **5. Lead-Team** | Zero-token roles (Developer / Programmer / Designer) | Role-proof gated |

### Zero-Token Lead Teams
Lead-team roles can be exercised **without holding any token**:

- Access granted purely by valid SAS attestation or ZK role proof
- Roles stored in the Compliance Registry (or ZK Registry) with capability bitmasks
- Compatible with Squads time-locks
- Ideal for pure identity-gated dApps and account-abstraction flows

| Role | Typical Capabilities | Proof Required |
|------|----------------------|----------------|
| Lead Developer | Deploy programs, update Transfer Hooks, manage Registry | Role + KYC + optional multi-sig |
| Lead Programmer | Circuits, risk engines, PRs | Role + KYC |
| Lead Designer | Marketplace UI, branding, gated content | Role + basic attestation |

---

## 🧾 Tax-First & Compliance-First Architecture

🏷️ `Tax` · `Compliance` · `Governance` · `Audit`

### Summary
Every workflow, repo, agreement, and ledger is designed to:

- Separate personal vs business finances & identity
- Maintain audit-ready documentation
- Enforce identity and authority
- Prevent accidental commingling

### Core Principles
1. **Separation of Funds & Identity** — No money or privileged action moves without documentation, approval, and Registry/ledger entry
2. **Immutable Records** — All actions logged in Loaner Ledger patterns, Agreements, Workflow/Transfer Hook logs, and Compliance Registry events
3. **Automation Enforcement** — System prevents unauthorized transfers, missing documentation, unverified identities, and policy violations

---

## ⚙️ Enforcement Layer

### Compliance Registry

🏷️ `Registry` · `On-Chain` · `Compliance` · `Authority`

Canonical on-chain (or hybrid) directory of trusted KYC providers, wallet statuses & tiers, roles & capability bitmasks, jurisdiction policies, and versioned policy templates.

- PDA-based lookups for low-latency enforcement
- Versioned entries for auditability
- Supports both clear-text and ZK (commitment / Merkle-root) variants
- Single source of truth for Transfer Hooks, marketplaces, and zero-token gates

### Solana Attestation Service + KYC

🏷️ `KYC` · `Identity` · `Security` · `SAS`

- Identity verification via real KYC providers
- Portable, reusable SAS credentials
- Signature / attestation validation
- Authority enforcement and sanctions screening
- Optional upgrade path to ZK credentials for selective disclosure

No workflow or transfer proceeds without a valid attestation.

### Token-2022 Transfer Hooks

🏷️ `Automation` · `Token-2022` · `Enforcement` · `Security`

Continuous on-chain enforcement:

- Every transfer is intercepted and validated against the Compliance Registry or a ZK proof
- Permanent Delegate enables recovery / administrative controls (via Squads + time-lock)
- Freeze Authority for temporary locks
- DefaultAccountState for controlled account initialization

---

## 💳 Tiered Role-Access Marketplace

🏷️ `Marketplace` · `Roles` · `Lending` · `Compliance`

<p align="center">
  <img src="assets/polar-checkout-qr-verified-badge.jpg" alt="Polar Checkout QR Verified" width="120">
</p>

Listings, purchases, and role grants are gated by:

- Compliance Registry status
- Tier / role checks
- Optional zero-token proofs
- **Polar MoR / verified checkout flows** (QR-driven, tax-compliant, identity-gated)

Supports both token-gated and pure credential-gated (tokenless) experiences.

> **Polar Checkout QR Verified** — Official cryptographic trust signal for autonomous commerce and verified payments.

---

## 🧬 Privacy Layer

Powered by the **[Aurora ZK Cryptography Framework](https://github.com/GitDigital-Solana/Aurora-zk-cryptography-framework)** — the cryptographic engine for zero-knowledge proofs, commitments, and on-chain verification on Solana.

### Aurora ZK (Core Cryptographic Dependency)

Aurora provides the production-grade primitives this SDK relies on:

| Aurora Capability | Used by Compliance SDK for |
|-------------------|----------------------------|
| Optimized Groth16 verifier (low CU) | On-chain verification of ZK Identity, ZK Registry membership, and ZK Age proofs |
| alt_bn128 + BLS12-381 field arithmetic | Core elliptic-curve operations for all proofs |
| Pedersen commitments & ElGamal | Confidential attributes, range proofs, selective disclosure |
| Plonky2 (experimental) | Future recursive / cheaper proofs |
| Token-2022 + ZK Compression compatibility | Native fit with Transfer Hooks and compressed state |
| Off-chain prover + on-chain notary pattern | Heavy math runs off-chain; lightweight attestation is recorded on-chain |

> Aurora is treated as a first-class sister project. This SDK does not re-implement the same cryptographic primitives.

### Tokenless (Zero-Token) Models
Access control without requiring any SPL / Token-2022 token. Users prove attributes (KYC status, age, jurisdiction, accreditation, role) via ZK credentials or SAS attestations.

### ZK Identity & ZK Registry
- Portable zero-knowledge identity credentials with selective disclosure
- Merkle-root / commitment-based registry
- Users prove membership or policy satisfaction + nullifier without revealing clear-text status
- Proofs generated and verified via Aurora

### ZK Age Verification & FHE
- Circuits that prove age ≥ threshold (or range) without revealing date of birth
- Fully Homomorphic Encryption for computation on encrypted compliance data (risk scores, attributes) — hybrid off-chain FHE + on-chain ZK proof of correct computation (Aurora + FHE layer)

Compliance remains foundational whether the path is clear-text or zero-knowledge.

---

## 🚀 Quick Start

```bash
# Clone
git clone https://github.com/Gitdigital-products/solana-kyc-compliance-sdk.git
cd solana-kyc-compliance-sdk

# Build Rust program
cd programs/compliance_registry
cargo build-bpf

# Build TypeScript SDK
cd ../../sdk/typescript
npm install && npm run build
```

### Minimal Client Example

```typescript
import { ComplianceClient } from "@gitdigital/solana-kyc-sdk";

const client = new ComplianceClient({
  connection,
  registryProgramId,
});

// Check wallet status
const status = await client.getWalletStatus(wallet.publicKey);

if (!status.isCompliant) {
  throw new Error("Wallet not registered or attestation expired");
}
```

---

## 🛠️ Preferred Stack & Multi-Language Support

🏷️ `Performance` · `Security` · `Polyglot` · `MLOps`

On-chain programs stay in **Rust + Anchor** (Token-2022, Transfer Hooks, Registry).  
Off-chain risk engines, FHE kernels, secure gateways, oracle adapters, and agent runtimes use the languages below for speed, safety, and lower operational cost.

| Language | Primary Strengths | How it helps this SDK |
|----------|-------------------|-----------------------|
| **TypeScript** | Ubiquitous Solana client ecosystem, strong typing, excellent DX | Primary client SDK, dApp front-ends, Registry/SAS orchestration, type-safe policy engines |
| **Julia** | Extreme numerical / scientific performance (LLVM), excellent for ML & Monte-Carlo | Off-chain AML risk engines, continuous scoring, portfolio/jurisdiction risk aggregation, scientific ZK parameter tuning |
| **Mojo** | Python-like ergonomics + C++/Rust-level speed, MLIR-based, SIMD/GPU targeting | High-throughput FHE kernels, confidential risk scoring, AI-augmented sanctions screening, deterministic financial compute |
| **Ballerina** | Cloud-native, integration-first, first-class security (mTLS, JWT, OAuth2) | Secure API gateways between KYC providers ↔ SAS ↔ Compliance Registry, Travel-Rule messaging, oracle ingestion |
| **V** | Extremely fast compilation & runtime, memory-safe by default, tiny binaries | Fast off-chain verifiers, lightweight client-side tooling, high-frequency status polling against the Registry |
| **Zig** | Manual memory control + strong safety, excellent C interop, no hidden control flow | Low-level FHE primitives, BPF-adjacent tooling, high-assurance crypto helpers, performance-critical side services |
| **Nim** | Python-like productivity + C-level performance, powerful metaprogramming | Rapid development of secure services, policy engines, oracle adapters, internal tooling |
| **Kotlin** | Strong static typing, null safety, coroutines, excellent JVM interop | Secure microservices, enterprise KYC/AML integration, concurrent Registry/oracle handling, multiplatform wallet logic |
| **Carbon** *(experimental)* | C++ successor with better safety & modern generics | Future systems-level components that interoperate with existing C/C++ crypto or FHE libraries |

**Guidance**
- Keep **on-chain** code in Rust + Anchor.
- Use **TypeScript** as the primary client and orchestration language.
- Use **[Aurora ZK](https://github.com/GitDigital-Solana/Aurora-zk-cryptography-framework)** for all zero-knowledge proof generation and on-chain verification primitives.
- Prefer the languages above for off-chain risk engines, FHE nodes, secure gateways, and high-assurance modules.
- Languages that reduce attack surface (Ballerina’s built-in security, V/Zig immutability & bounds checks, Mojo ownership) and lower cost (faster runtimes → fewer machines) are preferred.
- A top-level **Makefile** unifies polyglot builds (Rust + TS + Julia/Mojo/Zig/Kotlin/etc.).

These languages make the compliance engines, risk scoring, FHE computations, and autonomous agent loops **faster, cheaper, and more secure**.

### Planned `/lang` Directory Structure

Language-specific interop lives inside the main repository for now (clean extraction into dedicated repos later if needed):

```text
lang/
├── julia/          # AML risk engines, Monte-Carlo scoring, ZK parameter tuning
├── mojo/           # FHE kernels, confidential risk scoring, sanctions screening
├── v/              # Fast off-chain verifiers, lightweight tooling
├── zig/            # Low-level FHE primitives, high-assurance crypto helpers
├── ballerina/      # Secure API gateways, Travel-Rule, oracle ingestion
├── nim/            # Policy engines, oracle adapters, internal services
├── kotlin/         # Secure microservices, enterprise KYC/AML integration
└── README.md       # Interop contracts, FFI/gRPC boundaries, build notes
```

Each language folder will contain:
- Thin interop wrappers (calling the core Registry / SAS / Transfer Hook surface)
- Minimal examples
- Build instructions
- Clear interface documentation

This keeps the core focused while making the polyglot surface easy to discover and later extract.

---

## 📜 Legal & Identity-Verified Agreements

🏷️ `Agreements` · `Identity` · `Compliance`

All agreements are:

- Legally binding
- Identity-verified (SAS or ZK)
- Signature-required
- Immutable

**Types**
1. Founder / Loan Agreements — dual-signature, KYC-verified
2. Contributor Agreements — role-based, authority-scoped
3. Operational / Marketplace Agreements — workflow-generated

---

## 🛡️ Security & Error Handling

All programs and clients return structured, human-readable errors. Never emit bare numeric codes.

| Code | Meaning |
|------|---------|
| `NOT_REGISTERED` | Wallet not in Compliance Registry |
| `MISSING_OR_EXPIRED_KYC` | Attestation missing or expired |
| `SANCTIONED` | Wallet on restricted list |
| `MISSING_LEAD_ROLE` | Required lead-team role not present |
| `ZERO_TOKEN_ROLE_PROOF_FAILED` | Zero-token role proof failed |
| `INVALID_ZK_PROOF` | ZK verification or nullifier failure |
| `UNDER_AGE` | Age circuit failed |
| `POLICY_VIOLATION` | Transfer Hook rejected |
| `MULTISIG_REQUIRED` | Privileged action needs Squads + time-lock |
| `FHE_ERROR` | FHE ciphertext or key issue |

---

## 📚 Documentation & Standards

🏷️ `Docs` · `Templates` · `Standards`

- **Documentation Wizard** — automates README generation, agreement templates, ledger/Registry patterns, onboarding docs, and badge walls
- **Templates Library** — reusable modules for agreements, READMEs, workflows, and contributor onboarding
- **Badge Catalog** — official GitDigital Solana badges across Governance, Automation, Lending/RWA, Documentation, Privacy, Solana Signals, and Readiness

### Related References
- **[Aurora ZK Cryptography Framework](https://github.com/GitDigital-Solana/Aurora-zk-cryptography-framework)** — Core cryptographic engine (Groth16, alt_bn128, Pedersen, ElGamal, Plonky2)
- [Compliance Registry Design](references/compliance-registry.md)
- [Tiered Marketplace](references/tiered-marketplace.md)
- [Privacy / ZK / FHE](references/privacy-zk-fhe.md)
- [Zero-Token Lead Teams](references/zero-token-lead-teams.md)
- [Solana Ecosystem Submission](docs/SOLANA-ECOSYSTEM-SUBMISSION.md)
- [Demo Design](docs/DEMO-DESIGN.md)
- [ZK Identity Architecture](docs/ZK-IDENTITY-ARCHITECTURE.md)

---

## 🏷️ Badge Catalog

| Category | Examples |
|----------|----------|
| Governance | Governance · Authority · Compliance |
| Enforcement | Registry · Transfer Hook · SAS · KYC |
| Marketplace / RWA | Credit Authority · Loaner Ledger · Marketplace |
| Privacy | ZK · FHE · Tokenless · Selective Disclosure · Aurora ZK |
| Documentation | Docs · Templates · Wizard · Badge Catalog |
| Solana Signals | Solana Aligned · Grant Candidate · Security Ready |
| Readiness | Sponsor Ready · DD Ready · Enterprise Ready |

---

## 💼 Support

<script src="https://liberapay.com/GitDigital_liberapay/widgets/button.js"></script>
<a href="https://liberapay.com/GitDigital_liberapay/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a>
<a href="https://ko-fi.com/gitdigital"><img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Buy Me a Coffee at ko-fi.com"></a>

---

## 🧾 License & Ownership

**Author & Code Owner:** Rickcreator87 (@Rickcreator87)

Licensed under the **MIT License**.  
See `LICENSE`, `CODEOWNERS`, and `AUTHORS.md`.

---

**GitDigital Solana** — Compliance that lives on-chain.  
Transparent when you need it. Zero-knowledge when you require it.
