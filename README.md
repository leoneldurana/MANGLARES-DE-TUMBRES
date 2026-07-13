
### A Multijurisdictional Tokenized Ecosystem for Blue Carbon Credits
*Final Project — Innovating for a Sustainable Future Hackathon*

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)


**🔗 Live Dashboard Demo:** `https://leoneldurana.github.io/MANGLAR-TUMBES-/`
**🔗 Pitch Deck:** 
**🔗 Video Demo:** 

---

## 📌 Project Name

**Blue-Carbon TTF (Manglar Tumbes)** — a Transferable Tokenized Framework (TTF) that converts drone- and satellite-verified mangrove restoration data into on-chain blue carbon credits (tCO2eq), deployed on the LACNet EVM-compatible testnet.

---

## 👥 Team Members & Roles

| Member Name | Role / Specialty | Key Contribution |
| :--- | :--- | :--- |
| Duran Azaña, Leonel Lorenzo | Blockchain & Solidity Engineer | Smart contract development (`MangroveCarbonToken.sol`) & LACNet testnet deployment |
| Espettia Salazar, Guimar Alan Julian | Frontend & UX/UI Designer | Web3 dashboard integration & user journey optimization |
| Herrera Tejada, Ismael Leonardo | Project Manager & Research Analyst | Blue carbon research, MRV/jurisdictional analysis, & pitch strategy |
| Carranza Rojas, Jhon Alexander | Strategy & Documentation | Open-source release strategy & technical documentation |

---

## 🌍 The Problem

Mangrove forests are among the most carbon-dense ecosystems on Earth, yet remain among the most threatened. The **Santuario Nacional Los Manglares de Tumbes** (2,972 hectares — the largest mangrove extension in Peru) stores an estimated **1,786,486 megagrams of carbon (~6.55 million tonnes of CO2)**, at a density of 366.61–458.72 MgC/ha. Despite this, the ecosystem is degraded by illegal deforestation for shrimp-farming ponds (*langostineras*).

The deeper issue is structural: coastal cooperatives that depend on the mangrove (crab, shrimp, and *concha negra* harvesting) are **excluded from the value chain** of the carbon credits their conservation work generates. Traditional carbon registries are centralized, opaque, and vulnerable to greenwashing and double-counting.

This directly implicates **SDG 13 (Climate Action)** and **SDG 14 (Life Below Water)**.

---

## ✅ The Solution

Blue-Carbon TTF replaces the opaque centralized registry model with an **immutable, auditable, multijurisdictional smart contract**:

- Drone/satellite-verified restoration data → minted directly as TTF (tCO2eq) credits
- Every minting event **automatically distributes revenue** to stakeholders (see below)
- Zero-gas participation for coastal cooperatives via a gasless meta-transaction layer
- Designed from day one to operate across **Peru, Ecuador, and Colombia**

---

## 🛠️ Technologies Used

| Layer | Technology | Purpose |
|---|---|---|
| Smart Contracts | **Solidity** | Implements `MangroveCarbonToken.sol`: TTF minting, jurisdictional parameters, circular-economy fund distribution |
| Development Environment | **Remix EVM (IDE)** | Write, compile, test, and deploy contracts without local setup |
| Network | **LACNet Open Pro-Testnet & EVM** | Zero-GAS-fee execution across Peru, Ecuador, and Colombia's regulatory frameworks |
| Gasless Transaction Layer | **BaseRelayRecipient** | Enables cooperatives to transact without holding native gas tokens |
| MRV & Data Integrity | **MRV Oracle Simulation & IPFS** | Simulates drone-based hectare verification; pins imagery/data to IPFS |
| Web3 Integration | **Ethers.js** | Bridges the frontend with the deployed smart contract |
| Frontend | **HTML5 / Tailwind CSS / FontAwesome / Vanilla JavaScript** | Powers the LACNet Protocol Dashboard: MRV panel, revenue distribution view, live terminal log |

---

## 💰 Tokenomics — Revenue Distribution per Minting Event

Every TTF minting event is split automatically by the smart contract:

| Stakeholder | Share |
| :--- | :---: |
| 🟢 Coastal Communities | **55%** |
| 🔵 Technology / Platform | **20%** |
| 🟣 MRV Verification | **15%** |
| 🟠 Nursery Reinvestment | **10%** |

---

## 📈 Pilot Traction & Projected KPIs

**Current pilot results:** 40 hectares restored · 860 TTF (tCO2eq) minted · 9 active coastal cooperatives · **+22%** increase in *concha negra* capture in restored zones.

| Metric | Year 1 | Year 2 | Year 3 |
| :--- | :---: | :---: | :---: |
| Mangrove Hectares Restored (Cumulative) | 40 | 250 | 800 |
| TTF Credits Minted (tCO2eq, Cumulative) | 860 | 5,375 | 17,200 |
| Coastal Cooperatives Engaged | 9 | 30 | 80 |
| Jurisdictions Live (Peru / Ecuador / Colombia) | 1 | 2 | 3 |

*Figures are illustrative projections and will be recalibrated against real pilot-phase data.*

---

## 🗺️ Roadmap

| Horizon | Timeline | Focus |
| :--- | :--- | :--- |
| **Horizon 1** | Months 1–3 | Validation & Community Onboarding (contract audit, cooperative onboarding, MRV calibration) |
| **Horizon 2** | Months 4–6 | Automation & Gamification (satellite/drone automation, NFT verification badges) |
| **Horizon 3** | Months 7–12 | Multijurisdictional Expansion & DAO Governance (Ecuador/Colombia rollout, DAO transition) |

---

## 📂 Repository Structure

```
MANGLAR-TUMBES-/
├── index.html                       ← LACNet Protocol Dashboard (live demo)
├── README.md                        ← this file
├── LICENSE                          ← MIT open-source license
├── /contracts
│   └── MangroveCarbonToken.sol      ← Solidity smart contract
└── /presentation
    └── BlueCarbon_PitchDeck.pdf     ← 10-slide executive pitch deck
```

---

## 📜 References

- Actualidad Ambiental. (2025, March 4). *Conoce al manglar: la especie principal del Santuario Nacional Los Manglares de Tumbes*. https://www.actualidadambiental.pe/conoce-al-manglar-la-especie-principal-del-santuario-nacional-los-manglares-de-tumbes/
- Ecoticias. (2026, May 17). *Perú hace historia con un proyecto pionero de carbono azul...*. https://www.ecoticias.com/eco-america/peru-hace-historia-con-un-proyecto-pionero-de-carbono-azul-que-va-a-transformar-como-nunca-antes-los-manglares-de-tumbes
- Mongabay Latam. (2026, April 21). *Entre desafíos técnicos y regulatorios, nace en Perú el primer proyecto de carbono azul...*. https://es.mongabay.com/2026/04/desafios-peru-primer-proyecto-carbono-azul-manglares-tumbes/
- United Nations. (n.d.). *Goal 13: Climate Action*. https://sdgs.un.org/goals/goal13
- United Nations. (n.d.). *Goal 14: Life Below Water*. https://sdgs.un.org/goals/goal14

---

## 📄 License

This project is released under the **MIT License** — see [LICENSE](./LICENSE) for details.
TE.md…]()





