# REBEKA: Real Estate Blockchain Ekosystem Arbitrum

**REBEKA** is a professional RWA (Real World Asset) infrastructure designed to scale land property tokenization. By bridging the Mexican legal framework with the **Arbitrum** network, we provide a robust platform for managing large-scale properties under a secure, permissioned, and transparent environment.

Our ecosystem is designed to support diverse real estate strategies through a modular approach, ensuring that each property asset is backed by institutional-grade technology and legal certainty.

---

## 📂 Project Structure & Source Code

To maintain an enterprise-grade architecture, our codebase is divided into modular repositories within our GitHub Organization. You can explore the code here:

* **[⛓️ Smart Contracts (Arbitrum & Fhenix)](https://github.com/REBEKA-Projects/rebeka_contracts)**: Contains the Solidity code for the Sovereign Permissioned Layer and the $RWC1 FHE integration.
* **[🖥️ Frontend (Web3 dApp)](https://github.com/REBEKA-Projects/FrontEnd)**: The Next.js/React investor gateway and UI.
* **[⚙️ Backend / Node](https://github.com/REBEKA-Projects/rebeka_mocked_back)**: (Si aplica) The off-chain infrastructure and API connections.

## 🏗️ Core Infrastructure & Strategy

REBEKA is built to support three fundamental investment objectives, adaptable to each property’s specific needs:

* **EXIT (Liquidation):** Streamlined tokenization for full asset sale and capital recovery.
* **GROWTH (Appreciation):** Focused on long-term value increase through strategic land holding and development.
* **YIELD (Income):** Designed for properties that generate recurring cash flow through operations or leasing.

### Technical Foundation

* **RWAPermissionedERC20 Standard:** We have developed a custom **Permissioned ERC-20 layer**. This architecture ensures that asset ownership is strictly governed by internal compliance logic. No transfer is executed unless the parties are verified within our registry, providing a sovereign and cost-efficient alternative for regulated assets.
* **Institutional Governance (Multisig):** Fund management is secured via a **Gnosis Safe Multisig**. This "Human-in-the-loop" governance model ensures that all capital distributions—including property-specific reserves and owner payouts—are executed with multi-party oversight, aligning on-chain activity with the legal mandates of the property's Fideicomiso (Trust).
* **Survival Vault Concept:** Every project within REBEKA integrates a dedicated reserve fund. This vault ensures the asset remains debt-free by covering long-term operational costs (such as taxes and maintenance) directly from the initial funding phase.



---

## 📂 REBEKAProjects Ecosystem

The REBEKA infrastructure is organized into specialized modules:

* **`rebeka_contracts`**: The core protocol featuring the `RWAPermissionedERC20` contract and role-based access control (RBAC).
* **`FrontEnd`**: The professional investor gateway for onboarding, KYC synchronization, and asset management.
* **`REBEKA` (Root)**: High-level architectural documentation, legal-technical frameworks, and global ecosystem governance.

---

## 🚀 Buildathon Roadmap

* **V1 (Current):** Full deployment of the Permissioned Token architecture and Multisig governance on **Arbitrum Sepolia**.
* **Phase 2:** Optimization of the "Survival Vault" logic and integration of advanced reporting for institutional transparency.
* **Phase 3:** Onboarding of the first large-scale pilot property under the Growth/Exit model.

---
*REBEKA: The Institutional Infrastructure for Liquid Real Estate on Arbitrum.*
## 🔐 Project Identity
* **Official Admin Wallet:** `0x111783b2e149C62bd8f32ba4007ea58583EBBA53`
* **Network:** Arbitrum Sepolia (Testnet) / Arbitrum One (Mainnet)

> **Note:** This wallet is the designated owner for the REBEKA smart contracts and the recipient of any hackathon bounties.

---

## 🔐 Proof of Deployment: Institutional Privacy (FHE)

To demonstrate REBEKA's "Confidential-by-Design" architecture, we integrated **Fhenix (Fully Homomorphic Encryption)**. This ensures that while transactions are strictly validated on a public ledger, sensitive financial data—such as investment amounts and wallet balances—remains mathematically encrypted and hidden from third parties.

### Smart Contract Details
* **Network:** Arbitrum Sepolia (Testnet)
* **Token Name:** RWA Confidential 1 (`$RWC1`)
* **Confidential Token Address:** `0xe3A879a1e56FC801CaCf128eD1ddbadEc43e272a`

### 🕵️‍♂️ Audit the FHE Integration Yourself
You can verify the confidentiality of our protocol directly on the block explorer. 

1. **Go to our live demo transaction:** [View on Arbiscan Sepolia](https://sepolia.arbiscan.io/inputdatadecoder?tx=0x600ebd71064cb6c9ccc35b7b4e80d264a52f0e3c17b67b6e7970a4e6b17edaff)
2. Scroll down to the **"Input Data"** section.
3. Click the **"Decode Input Data"** button.
4. **The Result:** Notice that the transferred amount is not visible as plain text. Instead, the explorer returns an encrypted **Ciphertext**, proving that our FHE integration successfully masks institutional capital movements.

## 👥 The Team
* **Rom:** Strategy & Web3 Consulting.
* **Artur:** Lead Smart Contract Engineer (Stylus/Rust).
* **Robin:** UI/UX & Product Design.

---
**Developed for the Arbitrum Buildathon NYC 2026.**

