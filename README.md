# NodeFlow DApp — Web3 Workflow Builder

NodeFlow is a Blockchain Workflow Automation DApp,On Aptos, inspired by tools like n8n, allowing developers to visually build decentralized workflows, deploy smart contracts, and automate on-chain logic — all inside a node-based interface.
This project aims to bring no-code style automation into Web3, combining wallet connectivity, contract deployment, event triggers, backend automation, and IPFS storage into one unified experience.

---
# Demo Video  Link :
```

```
---
# Project PPT Link :
```

```
---
# Project Overview

* ## NodeFlow is built with:

 * Next.js + TailwindCSS → Modern frontend & UI
 * Solidity → Smart contracts
 * Node.js + TypeScript → Backend automation engine
 * Wagmi + Ethers.js → Wallet connection & on-chain interactions
 * Pinata (IPFS) → Storage for files / metadata
 * Alchemy RPC → Blockchain provider
 * (Optional) AI Modules → Contract generation, analysis, node suggestions


---

# Features

##  Workflow & Automation
* Visual node-based workflow builder
* Drag-and-drop automation similar to n8n / Zapier
* Real-time execution logs & result tracking

##  Smart Contract Management
* Deploy smart contracts directly from the DApp
* Call contract functions
* Event-based triggers
* Multi-chain support (e.g., Sepolia, Polygon, etc.)

##  Wallet & Connectivity
* Wallet connection via Wagmi + WalletConnect
* Supports MetaMask & multi-chain wallets

##  Storage Layer
* Upload files / JSON to IPFS using Pinata
* Store workflow metadata in decentralized storage

##  Optional AI Layer
* AI-assisted contract generation
* Contract vulnerability analysis
* Auto-node generation based on user workflow prompts


---
# Tech Stack

| Layer           | Technology                  |
| --------------- | --------------------------- |
| Frontend        | Next.js, React, TailwindCSS |
| Backend         | Node.js, TypeScript         |
| Smart Contracts | Solidity                    |
| Wallet          | Wagmi, Ethers.js            |
| Storage         | IPFS via Pinata             |
| RPC Provider    | Alchemy                     |
| Automation      | Node-based custom engine    |


---

# Project Structure
```
NodeFlow/
├── app/                  # Next.js app router pages & routes  
├── components/           # UI components (React + Tailwind)  
├── contracts/            # Solidity smart contracts  
├── lib/                  # Helper libraries (web3, IPFS, utilities)  
├── config/               # Contract config (ABI, addresses)  
├── store/                # State management  
├── types/                # TypeScript interfaces & types  
├── public/               # Static assets  
│
├── package.json
├── tsconfig.json
├── tailwind.config.ts
├── next.config.ts
└── README.md

```

---

# Project Setup Instructions

## 1)  Install Prerequisites
* VS Code
     
```
https://code.visualstudio.com/download

```

* Node.js (v20 recommended)

```
https://nodejs.org/en/download

```
---
# 2) Clone the Repository
```
git clone
cd Node_Flow
```
---
# 3) Install Dependencies
```
npm install
```
---
# 4) Configure Environment Variables
* Create a file:
```
.env.local
```
---
# 5) Start the Development Server
```
npm run dev
```
* Your app will run at:
```
http://localhost:3000
```
---
# Important Services Used

| Service                   | Purpose                         |
| ------------------------- | ------------------------------- |
| **Pinata**                | IPFS file & metadata storage    |
| **WalletConnect / Reown** | Seamless wallet connection      |
| **Formspree**             | Email forms (optional)          |
| **Alchemy**               | RPC, smart contract interaction |

---

# Contributing
* Pull requests are welcome!
* Ways to contribute:
* Add new workflow nodes
* Improve UI/UX for the builder
* Integrate more blockchain networks
* Add AI nodes
* Write docs / demos

---
# License
* NodeFlow is open-source under the MIT License.
* You may modify, use, and distribute freely.
---
# Thanks for Exploring NodeFlow on Aptos
Thank you for exploring NodeFlow — proudly built with suppo
rt for the Aptos blockchain, enabling fast, secure, and scalable Move-based automation. Your interest and contributions help push the Aptos ecosystem forward!




