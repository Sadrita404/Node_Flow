NodeFlow DApp
A Web3 Workflow Builder DApp inspired by tools like n8n — allowing users to visually automate blockchain tasks, deploy smart contracts, and build decentralized workflows.
Project Overview
NodeFlow is a Blockchain Workflow Builder DApp built using:
Next.js + TailwindCSS for the frontend
Solidity for smart contracts
Node.js + TypeScript for backend automation
Wagmi + Ethers.js for wallet connectivity and contract deployment
Optional AI integration for contract analysis and generation
Features
Visual workflow builder
Smart contract deployment
Multi-chain wallet connection
Backend automation engine
IPFS integration
Extensible node-based logic similar to n8n or Zapier
Tech Stack
Next.js
Node.js
TypeScript
Solidity
Wagmi
Ethers.js
Pinata (IPFS)
Alchemy RPC
Project Setup Instructions
Prerequisites
Make sure you have the following installed:
VS Code
Download: https://code.visualstudio.com/download
Node.js & NPM
Recommended Version: Node.js 20 or newer
Download: https://nodejs.org/en/download
Running the Project
1. Clone the Repository
git clone <repository-url>
cd nodeflow-dapp
2. Install Dependencies
npm install
3. Configure Environment Variables
Create a .env.local file in the project root and add:
NEXT_PUBLIC_ALCHEMY_KEY=your_key
NEXT_PUBLIC_WALLET_CONNECT_KEY=your_key
PINATA_JWT=your_jwt
You will need keys from:
Service	URL
Pinata (IPFS)	https://pinata.cloud/
WalletConnect (Reown)	https://docs.reown.com/cloud/relay
Alchemy	https://www.alchemy.com/
Formspree (optional)	https://formspree.io/
4. Run the Development Server
npm run dev
App will be available at:
http://localhost:3000
5. Compile & Deploy Smart Contracts
Navigate to the smart contract folder:
cd contracts
npm install
Compile:
npx hardhat compile
Deploy (example network):
npx hardhat run scripts/deploy.js --network sepolia
6. Connect Frontend with Smart Contract
Add deployed contract address & ABI inside:
/config/contract.js
Final Code Setup (If Using Final Source Code)
If you downloaded the ready-made source:
Add all required API keys
Install dependencies
Sync smart contract details
Run npm run dev
This will start the full DApp.
Important Services Used
Service	Usage
Pinata	IPFS file & JSON storage
WalletConnect / Reown	Wallet connection
Formspree	Form endpoints (optional)
Alchemy	RPC & smart contract interactions
Authors
NodeFlow DApp – Open Web3 Workflow Builder
Built with inspiration from decentralized automation platforms.