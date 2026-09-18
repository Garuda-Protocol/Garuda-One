# 🇮🇩 Garuda One

> **Sovereign Ethereum-compatible financial infrastructure for Indonesia's onchain economy.**

Garuda One is the proposed core infrastructure of **Garuda Protocol** — an Indonesia-native, Ethereum-compatible blockchain designed to enable regulated digital assets, stablecoins, payments, identity, and tokenized real-world assets to operate within an infrastructure aligned with Indonesia's regulatory and institutional environment.

Rather than building another general-purpose blockchain, Garuda One is designed around a specific objective:

> **Build the financial infrastructure layer for an increasingly onchain Indonesian economy.**

Garuda One aims to combine programmable blockchain infrastructure with identity, compliance, settlement, and financial primitives so that regulated digital services can be built on a common infrastructure layer rather than rebuilding fragmented compliance and financial rails application by application.

---

## Thesis

> **Indonesia should not only participate in the global onchain economy. It should have infrastructure capable of supporting its own regulated digital economy.**

Indonesia has a large and diverse financial and real economy spanning:

* Banks and financial institutions
* Digital payments
* MSMEs and enterprises
* Commodities
* Agriculture
* Infrastructure
* Property
* Capital markets
* Private credit
* Government and institutional assets
* Cross-border commerce

As these economic activities increasingly become digitized and programmable, blockchain infrastructure can provide a common settlement and execution layer.

However, general-purpose blockchains do not inherently provide the identity, compliance, institutional accountability, domestic settlement requirements, or regulatory controls required by regulated financial applications.

Garuda One is designed to address this infrastructure gap.

The core thesis is:

```text
Indonesian Economy
       ↓
Identity
       ↓
Compliance
       ↓
Settlement
       ↓
Digital Assets
       ↓
Financial Applications
       ↓
Global Connectivity
```

Garuda One therefore treats blockchain not merely as a technology for tokenizing assets, but as **financial infrastructure for regulated digital value transfer and programmable economic activity.**

---

# Why Garuda One?

The global blockchain ecosystem already provides highly capable execution and settlement networks.

Garuda One is not intended to compete with Ethereum on decentralization, liquidity, or general-purpose execution.

Instead, Garuda One focuses on the requirements of the Indonesian market.

### The problem

Financial institutions and enterprises entering onchain markets may need to solve multiple infrastructure problems independently:

* Identity verification
* KYC / AML
* Sanctions and risk screening
* Investor eligibility
* Asset transfer restrictions
* Regulatory controls
* Payment settlement
* Digital asset issuance
* Institutional custody
* Transaction monitoring
* Reporting
* Cross-border interoperability

This can create fragmented infrastructure across every application.

### The Garuda approach

Garuda One aims to make these capabilities available as **shared network infrastructure**.

```text
                    APPLICATIONS

       Payments    RWA    DeFi    Financial Services
           │        │      │           │
           └────────┴──────┴───────────┘
                          │
                  GARUDA PRIMITIVES
                          │
       ┌──────────────────┼──────────────────┐
       │                  │                  │
    Identity          Compliance         Settlement
       │                  │                  │
       └──────────────────┼──────────────────┘
                          │
                     GARUDA ONE
                          │
              Ethereum-Compatible Layer
                          │
                     Ethereum
```

The objective is to make **regulated financial functionality a property of the infrastructure**, rather than an entirely separate responsibility of every application.

---

# Core Principles

Garuda One is designed around six principles.

### 01 — Sovereign

Infrastructure serving Indonesian regulated financial activity should have clearly identified domestic operators, accountability, and infrastructure governance appropriate to the Indonesian jurisdiction.

Sovereignty does not mean isolation.

Garuda One remains designed for interoperability with the global Ethereum ecosystem.

---

### 02 — Ethereum-Compatible

Garuda One is designed to preserve compatibility with Ethereum's execution environment, standards, and developer ecosystem.

The objective is simple:

> **Developers should be able to build for Garuda without abandoning Ethereum.**

The intended environment includes compatibility with the broader EVM ecosystem, including technologies such as:

* Solidity
* EVM
* Foundry
* Hardhat
* ethers.js
* MetaMask
* ERC standards
* Account abstraction

This follows the broader Ethereum-equivalence philosophy demonstrated by Japan's MIZUHIKI, where Ethereum tooling and standards are intended to work without modification.

---

### 03 — Compliance by Infrastructure

Compliance should not need to be reconstructed independently by every application.

Garuda One is designed to explore shared infrastructure for:

* KYC
* AML
* Sanctions screening
* Wallet risk assessment
* Investor eligibility
* Transaction monitoring
* Asset restrictions
* Geographic restrictions
* Transfer controls
* Risk-based transaction limits

Applications can then build regulated financial products on top of common compliance primitives.

> **Compliance becomes infrastructure.**

This architecture is inspired by the principle demonstrated by MIZUHIKI, where identity, AML, sanctions screening, and risk-management functionality are positioned as shared platform-level primitives.

Garuda One does **not** assume that every compliance requirement can or should be enforced entirely onchain. Legal and regulatory requirements will determine the appropriate combination of onchain primitives, attestations, and regulated offchain entities.

---

### 04 — Identity-Preserving

Financial applications require verified participants.

Garuda One aims to support an identity layer based on:

```text
Real-World Identity
        ↓
Authorized Attestor
        ↓
Verification
        ↓
Credential
        ↓
Verified Wallet
        ↓
Applications
```

The objective is **not** to place personal information directly on a public blockchain.

Instead, the network should be able to verify claims such as:

* Identity verified
* KYC completed
* Jurisdiction
* Investor eligibility
* Credential validity
* Compliance status

while minimizing unnecessary exposure of personally identifiable information.

This follows the DID / Verifiable Credential direction explored by MIZUHIKI, where verification status can be represented without exposing personal information directly onchain.

---

### 05 — Settlement-First

A financial network ultimately needs a reliable way to move value.

Garuda One is therefore designed around programmable settlement infrastructure for:

* IDR-denominated value
* Stablecoins
* Tokenized securities
* Digital assets
* Payments
* Institutional settlement
* Cross-border transactions

Garuda One itself is infrastructure.

It does not inherently need to become the issuer of every stablecoin or financial asset on the network.

Instead:

> **Garuda provides the rails. Regulated institutions can provide the financial instruments.**

This distinction is important. MIZUHIKI, for example, explicitly describes itself as infrastructure rather than a stablecoin issuer, providing settlement and compliance infrastructure for regulated issuers.

---

### 06 — Global by Design

Sovereign does not mean isolated.

Garuda One is intended to connect Indonesian economic activity with the broader Ethereum ecosystem.

```text
Indonesia
   │
   ↓
Garuda One
   │
   ├── Ethereum
   ├── Arbitrum
   ├── Stablecoins
   ├── Global Liquidity
   └── Global Applications
```

The objective is:

> **Indonesia-native infrastructure with global interoperability.**

---

# Garuda One Architecture

Garuda One is envisioned as a layered financial infrastructure stack.

```text
┌─────────────────────────────────────────────────┐
│                  APPLICATIONS                   │
│                                                 │
│ Payments │ Lending │ RWA │ DeFi │ Enterprise   │
│ Markets  │ Treasury│ AI Agents │ Consumer      │
└───────────────────────┬─────────────────────────┘
                        │
┌───────────────────────┴─────────────────────────┐
│              FINANCIAL PRIMITIVES                │
│                                                 │
│ Tokenized Assets │ Credit │ Stablecoins         │
│ Payments │ Collateral │ Securities │ Funds      │
└───────────────────────┬─────────────────────────┘
                        │
┌───────────────────────┴─────────────────────────┐
│               GARUDA TRUST LAYER                 │
│                                                 │
│ Identity │ KYC │ AML │ Risk │ Attestation       │
│ Eligibility │ Transfer Rules │ Monitoring        │
└───────────────────────┬─────────────────────────┘
                        │
┌───────────────────────┴─────────────────────────┐
│                 GARUDA ONE L1                    │
│                                                 │
│ EVM │ Consensus │ Execution │ Settlement        │
│ Account Abstraction │ Smart Contracts           │
└───────────────────────┬─────────────────────────┘
                        │
┌───────────────────────┴─────────────────────────┐
│              ETHEREUM ECOSYSTEM                  │
│                                                 │
│ Ethereum │ Arbitrum │ Bridges │ Oracles         │
│ Liquidity │ Developers │ Standards               │
└─────────────────────────────────────────────────┘
```

The exact architecture remains subject to technical, regulatory, and institutional validation.

---

# Identity Infrastructure

Garuda Identity is envisioned as a reusable identity and credential layer for applications operating on the network.

Instead of requiring every application to independently perform the same verification process:

```text
User
 ↓
Authorized Identity Provider
 ↓
KYC / Verification
 ↓
Credential
 ↓
Garuda Wallet
 ↓
Multiple Applications
```

A verified credential could potentially be used across multiple applications while allowing each application to enforce its own eligibility requirements.

Potential credential types include:

| Credential    | Example                        |
| ------------- | ------------------------------ |
| Identity      | Verified natural person        |
| Jurisdiction  | Indonesian resident            |
| KYC           | KYC completed                  |
| AML           | Screening status               |
| Investor      | Eligible investor category     |
| Business      | Verified legal entity          |
| Institution   | Verified financial institution |
| Accreditation | Specific eligibility status    |

Personal information should remain outside the public blockchain wherever possible.

---

# Compliance Infrastructure

Garuda Compliance is intended to provide common infrastructure for regulated digital applications.

Potential primitives include:

```text
Identity Verification
        │
        ├── KYC
        ├── KYB
        └── Credential Verification
                │
                ↓
        Compliance Validation
                │
        ├── AML
        ├── Sanctions
        ├── PEP
        └── Risk Screening
                │
                ↓
        Transaction Controls
                │
        ├── Transfer Restrictions
        ├── Geographic Rules
        ├── Limits
        ├── Asset Eligibility
        └── Monitoring
```

The exact implementation will depend on Indonesian regulatory requirements and the participation of appropriately authorized entities.

Garuda One does not claim regulatory approval or compliance merely by implementing technical controls.

---

# Settlement Infrastructure

Garuda One is designed to become a programmable settlement layer for digital value.

Potential settlement assets include:

* Regulated IDR stablecoins
* Other regulated stablecoins
* Tokenized deposits
* Tokenized securities
* Digital representations of financial assets
* Other eligible settlement instruments

A simplified transaction could look like:

```text
Buyer
  │
  │ IDR / Stablecoin
  ↓
Garuda Settlement
  │
  ├── Compliance Check
  ├── Identity Check
  └── Transaction Rules
  │
  ↓
Tokenized Asset
  │
  ↓
Seller / Issuer
```

The network can provide programmable settlement while regulated entities remain responsible for issuance, custody, reserves, legal claims, and other obligations where applicable.

---

# Payments

Payments are a core use case of Garuda One.

Potential applications include:

### Domestic Payments

* Merchant settlement
* Enterprise payments
* B2B payments
* Payroll infrastructure
* Treasury movement

### Cross-Border Payments

* Remittances
* International settlements
* Export / import payments
* Global merchant settlement

### Programmable Payments

* Escrow
* Conditional settlement
* Recurring payments
* Machine-to-machine payments
* AI-agent transactions

The long-term objective is to make programmable digital value transfer accessible without requiring every payment application to independently build its own blockchain infrastructure.

---

# Tokenized Real-World Assets

RWA remains a major application category of Garuda One, but it is no longer the entire thesis.

Potential asset categories include:

* Government securities
* Corporate securities
* Funds
* Treasury products
* Commodities
* Receivables
* Private credit
* Infrastructure
* Property
* Trade finance
* Other legally eligible real-world assets

The asset lifecycle can be represented as:

```text
Real-World Asset
       ↓
Legal Structuring
       ↓
Verification / Attestation
       ↓
Tokenization
       ↓
Garuda Settlement
       ↓
Compliance Controls
       ↓
Liquidity
       ↓
Financial Applications
       ↓
Redemption / Settlement
```

The critical principle is:

> **Tokenization does not create legal ownership, liquidity, or economic value by itself.**

The underlying asset, legal structure, issuer, custodian, servicing arrangement, and regulatory framework remain essential.

---

# RWA Trust Model

Blockchain can provide strong guarantees about onchain state.

It cannot independently prove that an offchain asset exists, that an obligor will pay, or that a legal claim will be enforceable.

Therefore:

```text
BLOCKCHAIN CAN VERIFY

✓ Token ownership
✓ Transaction history
✓ Smart contract rules
✓ Onchain collateral state
✓ Settlement records

BLOCKCHAIN CANNOT ALONE VERIFY

✗ Physical asset existence
✗ Borrower solvency
✗ Legal enforceability
✗ Custodian solvency
✗ Offchain valuation
✗ Attestor honesty
```

Garuda therefore requires a broader trust architecture involving appropriate:

* Issuers
* Custodians
* Auditors
* Attestors
* Oracles
* Legal entities
* Servicers
* Financial institutions

---

# Financial Primitives

Garuda One aims to support a common infrastructure layer for programmable financial applications.

Potential primitives include:

### Stablecoins

Regulated digital representations of currency for settlement and payments.

### Tokenized Securities

Digital representations of eligible securities and financial instruments.

### Credit

Programmable lending, receivables financing, trade finance, and collateralized credit.

### Collateral

Tokenized assets usable within compliant financial applications.

### Funds

Onchain representations of eligible investment products.

### Treasury

Enterprise treasury management and programmable settlement.

### Payments

Domestic and cross-border programmable value transfer.

These primitives should emerge from validated use cases rather than being created solely for technical completeness.

---

# The Developer Economy

Garuda One is ultimately infrastructure for developers.

The objective is to allow developers to build financial applications without recreating the entire underlying trust stack.

Instead of:

```text
Developer
   ↓
Build Blockchain Integration
   ↓
Build KYC
   ↓
Build AML
   ↓
Build Identity
   ↓
Build Compliance
   ↓
Build Settlement
   ↓
Finally Build Application
```

Garuda aims toward:

```text
Developer
   ↓
Garuda Infrastructure
   │
   ├── Identity
   ├── Compliance
   ├── Settlement
   ├── Assets
   └── Financial Primitives
          ↓
      Application
```

Potential application categories include:

| Vertical   | Examples                                  |
| ---------- | ----------------------------------------- |
| Payments   | Merchant payments, remittance, settlement |
| Finance    | Lending, credit, treasury                 |
| RWA        | Securities, funds, commodities, property  |
| Commerce   | Merchant finance, trade finance           |
| Consumer   | Savings, loyalty, financial applications  |
| Enterprise | Treasury, settlement, accounting          |
| AI         | Autonomous payments and financial agents  |
| DeFi       | Compliant onchain financial markets       |

---

# Indonesia → Global

Garuda One is:

> **Indonesia-native, not Indonesia-only.**

The network is intended to provide a domestic foundation while remaining connected to global infrastructure.

```text
INDONESIAN ECONOMY
        │
        ↓
    GARUDA ONE
        │
   ┌────┼────┐
   ↓    ↓    ↓
Ethereum Arbitrum Stablecoins
   │    │    │
   └────┼────┘
        ↓
GLOBAL LIQUIDITY
        │
        ↓
GLOBAL APPLICATIONS
```

Indonesian financial assets and applications should be able to interact with global onchain markets where legally and technically appropriate.

---

# Sovereignty

Sovereignty is not defined as isolation from the global blockchain ecosystem.

It refers to the ability to maintain clear domestic accountability over critical infrastructure.

Garuda One will therefore explore:

* Domestic validator infrastructure
* Identifiable infrastructure operators
* Indonesian legal accountability
* Appropriate data residency
* Domestic institutional participation
* Regulatory-aligned network governance

This architecture is directly inspired by the sovereign Ethereum-equivalence model described by Japan Smart Chain, where validators are identified and located domestically while the network remains Ethereum-compatible.

The exact validator and governance architecture for Garuda remains an open research question.

---

# Network Governance

Garuda One is expected to require a governance model appropriate for infrastructure serving regulated financial activity.

Potential governance domains include:

* Protocol upgrades
* Validator admission
* Infrastructure standards
* Compliance primitive standards
* Emergency procedures
* Security policies
* Ecosystem standards

Governance design must balance:

```text
Decentralization
       +
Accountability
       +
Regulatory Compatibility
       +
Security
```

The final governance structure has not yet been determined.

---

# Security

Garuda One treats security as a network-level concern.

Security research will cover:

### Blockchain Security

* Consensus security
* Client diversity
* Validator security
* Key management
* Network attacks

### Smart Contract Security

* Contract audits
* Formal verification where appropriate
* Upgrade security
* Permission management

### Financial Security

* Oracle manipulation
* Collateral fraud
* Double financing
* Asset misrepresentation
* Counterparty risk

### Identity Security

* Credential theft
* Attestor compromise
* Credential revocation
* Sybil resistance

### Compliance Security

* Sanctions screening
* Risk classification
* Transfer restrictions
* Monitoring
* Emergency controls

The objective is not merely to secure a blockchain.

> **The objective is to secure an onchain financial system.**

---

# Economic Model

Garuda One's economic model is under research.

Potential network economics may involve:

* Transaction fees
* Infrastructure services
* Stablecoin settlement economics
* Institutional services
* Developer infrastructure
* Network-level services

The protocol does not currently assume that a native speculative token is required.

A native token should only exist if it provides a clearly necessary protocol function such as:

* Network security
* Consensus
* Governance
* Economic coordination
* Spam prevention

If those functions can be achieved without a native asset, unnecessary tokenization should be avoided.

---

# Stablecoin Strategy

Garuda One is designed to support regulated stablecoin infrastructure rather than assuming Garuda itself must become a stablecoin issuer.

Potential architecture:

```text
Regulated Issuer
       ↓
Stablecoin
       ↓
Garuda One
       ↓
Payments / RWA / DeFi / Enterprise
```

This allows multiple regulated issuers and financial institutions to potentially participate in the network.

The objective is to create a **settlement ecosystem**, not necessarily a single Garuda-controlled currency.

---

# Institutional Infrastructure

Garuda One is designed with financial institutions and enterprises as first-class participants.

Potential participants include:

* Banks
* Payment service providers
* Securities firms
* Asset managers
* Custodians
* Exchanges
* Fintech companies
* Corporations
* Infrastructure providers
* Auditors
* Identity providers

Institutional participation is critical because regulated digital finance requires more than blockchain infrastructure.

It requires accountable organizations operating around the network.

---

# Network Effects

Garuda's long-term network effect is expected to emerge from infrastructure reuse.

```text
Institutions
     ↓
Assets
     ↓
Settlement
     ↓
Applications
     ↓
Users
     ↓
Developers
     ↓
More Applications
     ↓
More Financial Activity
     ↓
More Institutional Participation
```

However, this flywheel should not be assumed.

Garuda must first prove concrete demand through real users, real institutions, real assets, and real transactions.

---

# Roadmap

## Phase 01 — Research & Foundation

* [ ] Define Garuda thesis
* [ ] Regulatory research
* [ ] Sovereignty model
* [ ] Identity architecture
* [ ] Compliance architecture
* [ ] Settlement architecture
* [ ] RWA framework
* [ ] Economic model
* [ ] Institutional requirements
* [ ] Technical architecture

---

## Phase 02 — Core Infrastructure

* [ ] Garuda One architecture
* [ ] Validator framework
* [ ] EVM execution environment
* [ ] Ethereum interoperability
* [ ] Core protocol deployment
* [ ] Explorer
* [ ] Developer tooling
* [ ] Documentation

---

## Phase 03 — Trust & Compliance Layer

* [ ] Garuda Identity
* [ ] Credential infrastructure
* [ ] KYC primitives
* [ ] AML integrations
* [ ] Risk infrastructure
* [ ] Asset eligibility framework
* [ ] Transfer controls
* [ ] Attestation infrastructure

---

## Phase 04 — Settlement & Financial Infrastructure

* [ ] Stablecoin integrations
* [ ] Payment primitives
* [ ] Institutional settlement
* [ ] RWA primitives
* [ ] Tokenized financial assets
* [ ] Treasury infrastructure
* [ ] Credit primitives

---

## Phase 05 — Ecosystem

* [ ] Developer programs
* [ ] Hackathons
* [ ] Grants
* [ ] DApp incubation
* [ ] Institutional pilots
* [ ] Financial application ecosystem

Developer incentives will follow demonstrated infrastructure demand rather than precede it.

---

## Phase 06 — Global Connectivity

* [ ] Ethereum connectivity
* [ ] Arbitrum connectivity
* [ ] Cross-chain liquidity
* [ ] Global stablecoin infrastructure
* [ ] International RWA markets
* [ ] Global developer expansion

---

# Repository Structure

```text
garuda-one/

├── contracts/          # Core smart contracts
├── chain/              # Chain configuration and infrastructure
├── identity/           # Identity & credential infrastructure
├── compliance/         # Compliance primitives
├── settlement/         # Settlement infrastructure
├── assets/             # Tokenized asset primitives
├── packages/           # Shared development packages
├── scripts/             # Deployment & development scripts
├── docs/                # Technical documentation
├── tests/               # Test suites
└── README.md
```

> Repository structure is subject to change during early development.

---

# Garuda Protocol

Garuda One is the foundational infrastructure layer of the broader **Garuda Protocol** ecosystem.

```text
                         GARUDA PROTOCOL
                                │
        ┌───────────────────────┼────────────────────────┐
        │                       │                        │
        ↓                       ↓                        ↓
   GARUDA ONE            GARUDA IDENTITY         GARUDA COMPLIANCE
   Core Network          Identity Layer          Trust Layer
        │                       │                        │
        └───────────────────────┼────────────────────────┘
                                │
                        GARUDA SETTLEMENT
                                │
                 ┌──────────────┼──────────────┐
                 ↓              ↓              ↓
              Payments        RWAs          Finance
                 │              │              │
                 └──────────────┼──────────────┘
                                ↓
                       GLOBAL ECOSYSTEM
```

The ecosystem architecture remains subject to further research and validation.

---

# Development Status

🚧 **Early Research & Architecture**

Garuda One is currently in the research, thesis validation, and architecture phase.

The following areas remain under active development:

* Network architecture
* Validator model
* Identity architecture
* Compliance framework
* Settlement infrastructure
* Stablecoin strategy
* Economic model
* RWA framework
* Governance
* Institutional participation

Nothing in this repository should be interpreted as:

* A finalized financial product
* An investment offering
* A guarantee of regulatory approval
* A deployed financial infrastructure
* A representation that any proposed functionality is currently operational

Garuda One's architecture will evolve based on technical, regulatory, institutional, and market validation.

---

# Contributing

Garuda One is being developed with the long-term goal of creating open infrastructure for Indonesian and global developers, institutions, and builders.

Contribution guidelines and developer documentation will be published as the protocol matures.

---

# Links

**Garuda Protocol**

Coming soon.

**Documentation**

Coming soon.

**Developer Portal**

Coming soon.

**Explorer**

Coming soon.

---

# License

License information will be added as the protocol architecture and repository structure are finalized.

---

# Garuda Protocol

> **Indonesia's sovereign financial infrastructure for the onchain economy.**

**Ethereum-compatible.**

**Compliance-aware.**

**Built for regulated digital finance.**

**Starting in Indonesia.**

**Connected to the world.**
