## IYKYK DAO Token Model (Revised for Advanced Readers)

### 🔹 Overview

The IYKYK DAO token system is designed to integrate decentralized governance, cultural funding, and meaningful community engagement. It operates through a two-layer architecture:

1. **IYK Token (ERC-20, powered by Juicebox)** – This serves as the primary economic unit and governance mechanism. It enables users to participate in funding decisions, governance processes, and reward systems.
2. **Membership NFTs (Nouns-style architecture)** – These NFTs function as governance primitives, granting holders high-level control over the DAO. This includes authority over treasury strategy, Juicebox settings, and protocol evolution.

---

### 🔸 IYK Token: Core Functions and Economics

#### 1. Minting Process

* IYK tokens are minted when contributors deposit ETH into the Juicebox contract.
* The system launches with a fixed mint rate. Over time, this will evolve into a bonding curve model to reflect demand-based pricing.
* Each funding cycle allocates a percentage of newly minted IYK as a reserved pool for NFT holders.

#### 2. Earning and Distribution Mechanisms

* IYK is distributed as a reward for consumer participation in:

  * Event sign-ins
  * QR code activations
  * App downloads
  * Campaign missions and artist-led engagements
* Artists and sponsors can create custom campaigns—such as scavenger hunts—to distribute IYK tokens in innovative ways.

#### 3. Redemption and Deflation

* IYK tokens can be redeemed for:

  * Tickets to events
  * Exclusive merchandise
  * Travel and hospitality experiences
* Redeemed tokens are permanently burned, helping maintain supply equilibrium and minimize inflation.

---

### 🔸 IYK Token in Governance

#### 1. Voting Power and Staking

* IYK token holders vote on:

  * Allocations from the IYKYK Grant Treasury
  * Flows.wtf grant stream configurations
  * Prioritization of funding categories and community missions
* Voting rights are activated through staking, creating alignment and accountability among participants.

#### 2. Burn-Driven Voting Cycles

* Certain grant votes, especially high-impact ones, require burning tokens to cast votes. This disincentivizes spam voting and encourages long-term participation.

#### 3. Identity Verification

* Sybil resistance is implemented through integrations with:

  * Proof of Humanity
  * BrightID
  * Gitcoin Passport

These identity systems help ensure equitable governance by limiting duplicate accounts.

---

### 🔸 Membership NFTs: Governance and Benefits

#### 1. Launch Mechanism

* NFTs are distributed via a Nouns-style auction system.
* Holders receive:

  * Unique generative artwork
  * Full governance rights across DAO operations

#### 2. Powers of Governance

NFT holders influence key aspects of the protocol, including:

* Allocation parameters in Juicebox (e.g., mint rate, reserve ratio)
* Flows-based funding stream creation and management
* Grant approval structures
* Treasury management strategies and emergency procedures

#### 3. Reserved Token Allocation

* A portion of each funding cycle’s minted tokens (initially 25%) is reserved for NFT holders.
* These reserved tokens are claimable quarterly.
* The exact quantity is dynamically adjusted according to DAO revenue and Juicebox cycle performance, ensuring alignment between participation and incentives.

---

### 🔸 Treasury Architecture and Capital Allocation

Funds raised in each Juicebox cycle are automatically split:

* **50% → IYKYK DAO Treasury**

  * Supports operational and promotional activities tied to sponsorships and community programs
* **30% → Operations (via Gnosis Safe multisig)**

  * Funds staffing, marketing, tooling, and events
* **20% → IYKYK Grant Treasury**

  * Fuels the Flows.wtf system and community-initiated art/public goods projects

---

### 🔸 Token Supply Lifecycle

* Token supply is demand-driven, expanding via ETH contributions.
* Supply is curtailed through the burn mechanism when users redeem tokens.
* DAO governance maintains the authority to adjust mint rates and reintroduce burned tokens if strategically necessary.

---

### 🔸 Roadmap for Token Development

| Phase | Milestone          | Features                                           |
| ----- | ------------------ | -------------------------------------------------- |
| 1     | Launch             | Fixed-rate minting and NFT governance launch       |
| 2     | Ecosystem Growth   | Seasonal quests and artist-led activations         |
| 3     | Dynamic Minting    | Transition to a bonding curve via Juicebox upgrade |
| 4     | Treasury Expansion | Formalization of treasury governance and audits    |

---

### 🔸 Artist and Sponsor Toolkits

* Customizable toolkits empower creators and sponsors to:

  * Launch QR-based engagement quests
  * Propose mint events via the Nouns Buildr interface
  * Include embedded IYK airdrops with their NFT activations

---

### 🔸 Transparency and Reporting

The DAO maintains a quarterly reporting system including:

* Token issuance and burn logs
* Detailed breakdowns of treasury activity
* Performance analysis of funded grant streams
* Governance participation and proposals passed

---

### 🔸 Security and Risk Management

* Juicebox parameter changes and fund distributions are gated by:

  * On-chain governance with DAO oversight
  * Multisig emergency systems
  * Scheduled audits and bug bounty support

These mechanisms ensure DAO resilience against manipulation and unauthorized access.

---

### 🔸 Disclaimer

This document is intended for informational purposes only and does not constitute financial, legal, or investment advice. The IYKYK DAO and its associated systems are experimental and evolving. Participants should conduct their own research and consult with appropriate professionals before engaging with any aspect of the protocol.

