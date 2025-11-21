# MeowFi

MoMo is designed to be more than just another memecoin — it’s a lightweight, smooth, and interactive Web3 trading portal. With wallet connectivity, real-time token swapping, and a playful UI, MoMo brings together the excitement of meme culture with reliable blockchain tooling. Whether you're testing new ideas or exploring token swaps, MoMo makes the journey simple and enjoyable.

🌟 Features
🐾 Memecoin Landing Experience
A clean, engaging, and meme-powered interface that highlights the MoMo brand and community spirit.
🔄 DEX Swap Module
Swap $MOMO ↔ Sepolia ETH instantly using the integrated swap engine — fast, secure, and beginner-friendly.
🔗 Web3 Wallet Integration
Connect MetaMask or any EVM-compatible wallet to interact directly with MoMo smart contracts.
⚡ Fast & Responsive UI
Built with React, Tailwind, and ShadCN for a modern, polished, mobile-friendly experience.
🔒 Smart Contract Security
MoMo smart contracts are written in Solidity and rigorously tested with Foundry for reliability on the Sepolia testnet.
🎉 Community-Driven Branding
MoMo embraces playful visuals and meme culture to create a fun ecosystem that users will enjoy interacting with.

## 🛠 Tech Stack
- **Frontend:** React, Tailwind CSS, ShadCN
- **Blockchain:** Solidity, Foundry
- **Wallet Integration:** Ethers.js
- **Smart Contract Deployment:** Sepolia Testnet

## 📦 Installation

1. Clone the repository:
   ```sh
   git clone repo link
   cd meowfi
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```sh
   VITE_ALCHEMY_API_KEY=your_api_key
   VITE_CONTRACT_ADDRESS=your_contract_address
   VITE_WALLET_CONNECT_PROJECT_ID=your_project_id
   ```
4. Start the development server:
   ```sh
   npm run dev
   ```

## 🔗 Smart Contract Deployment (Foundry)
1. Install Foundry:
   ```sh
   curl -L https://foundry.paradigm.xyz | bash
   foundryup
   ```
2. Compile the contract:
   ```sh
   forge build
   ```
3. Run tests:
   ```sh
   forge test
   ```
4. Deploy to Sepolia:
   ```sh
   forge script script/Deploy.s.sol:Deploy --rpc-url https://sepolia.infura.io/v3/YOUR_INFURA_KEY --private-key YOUR_PRIVATE_KEY --broadcast
   ```

## 📜 License
This project is licensed under the MIT License.

---

Enjoy swapping with **MeowFi**! 🐱💰

