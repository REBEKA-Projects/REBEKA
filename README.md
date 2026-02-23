# REBEKA: Real Estate Blockchain Ekosystem Arbitrum

**REBEKA** is a professional RWA (Real World Asset) infrastructure designed to scale land property tokenization. By bridging the Mexican legal framework (Fideicomiso) with the **Arbitrum** network, we provide a robust platform for managing large-scale properties under a secure, permissioned, and highly confidential environment.

Our ecosystem is designed to solve the two biggest barriers for institutional capital entering Web3: strict legal compliance and financial privacy on public ledgers.

---

## 📂 Project Structure & Source Code

To maintain an enterprise-grade architecture, our codebase is divided into modular repositories within our GitHub Organization. You can explore the code here:

* **[⛓️ Smart Contracts (Arbitrum & Fhenix)](https://github.com/REBEKA-Projects/rebeka_contracts)**: Contains the Solidity code for the Sovereign Permissioned Layer and the $RWC1 FHE integration.
* **[🖥️ Frontend (Web3 dApp)](https://github.com/REBEKA-Projects/FrontEnd)**: The Next.js/React institutional investor gateway and UI.
* **[⚙️ Backend / Core API](https://github.com/REBEKA-Projects/rebeka_mocked_back)**: The off-chain infrastructure and data synchronization.

## 🏗️ Core Infrastructure & Technical Foundation

REBEKA replaces generic token models with a highly specialized compliance and privacy engine tailored for real-world legal mandates:

* **Sovereign Compliance (RWAPermissionedERC20):** We developed a custom Permissioned ERC-20 layer. This architecture ensures that asset ownership is strictly governed by internal compliance logic. No transfer is executed unless both wallets are KYC-verified by the Trust. Unauthorized attempts automatically `revert`, providing a sovereign and cost-efficient firewall directly on Arbitrum.
* **Confidential-by-Design (FHE Integration):** Institutional capital demands privacy. We integrated Fully Homomorphic Encryption (Fhenix) to ensure that sensitive financial data—such as investment amounts and wallet balances—remains mathematically encrypted and hidden from third parties, even on a public ledger.
* **Omnichain Future (LayerZero):** While Arbitrum remains our single source of legal truth and settlement, our architecture is prepared to integrate cross-chain messaging, allowing REBEKA to attract borderless liquidity in the near future.

---

## 🔐 Proof of Deployment: Institutional Privacy (FHE)

To demonstrate REBEKA's "Confidential-by-Design" architecture, we integrated **Fhenix (Fully Homomorphic Encryption)**. This ensures that while transactions are strictly validated on a public ledger, sensitive financial data remains mathematically encrypted.

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

---

## 📂 REBEKAProjects Ecosystem Modules

The REBEKA infrastructure is organized into specialized modules:

* **`rebeka_contracts`**: The core protocol featuring the `RWAPermissionedERC20` contract and FHE token integrations.
* **`FrontEnd`**: The professional investor gateway for onboarding, KYC status visualization, and asset management.
* **`rebeka_mocked_back`**: The specialized backend infrastructure providing the API services and data synchronization required for institutional onboarding.
* **`REBEKA` (Root)**: High-level architectural documentation, legal-technical frameworks, and global ecosystem governance.

---

## 🎥 Project Demos

* **Official Pitch Video (Vision & Strategy):** [Watch on YouTube](https://youtu.be/-l_wf97nGWU)
* **Technical Demo Video (Product & FHE in Action):** [Watch on YouTube](https://youtu.be/V2LHD9zaVr0)

## 🚀 Buildathon Roadmap

* **V1 (Current):** Full deployment of the Sovereign Permissioned Token architecture and FHE privacy integration on **Arbitrum Sepolia**.
* **Phase 2:** Integration of LayerZero cross-chain messaging to enable omnichain liquidity sourcing.
* **Phase 3:** Onboarding of the first large-scale pilot property under a Mexican Irrevocable Trust (Fideicomiso) onto Mainnet.

---
*REBEKA: The Institutional Infrastructure for Liquid Real Estate on Arbitrum.*

## 🔐 Project Identity
* **Official Admin Wallet:** `0x111783b2e149C62bd8f32ba4007ea58583EBBA53`
* **Network:** Arbitrum Sepolia (Testnet) / Arbitrum One (Mainnet)

> **Note:** This wallet is the designated owner for the REBEKA smart contracts and the recipient of any hackathon bounties.

---

## 👥 The Team
* **Rom:** Strategy & Web3 Consulting.
* **Artur:** Lead Smart Contract Engineer (Stylus/Rust).
* **Robin:** UI/UX & Product Design.

* 
**Developed for the Arbitrum Buildathon NYC 2026.**

