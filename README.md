## 🚀 Introduction
This is a decentralized NFT marketplace built on the Ethereum blockchain, developed for **HackIndia 2025**. It enables users to mint, buy, and sell NFTs securely using smart contracts deployed on Ethereum.

## 🛠️ Tech Stack
- **Blockchain**: Ethereum (Solidity, Hardhat)
- **Smart Contracts**: Solidity
- **Development Framework**: Hardhat
- **Frontend**: React.js / Next.js (if applicable)
- **Wallet Integration**: MetaMask, WalletConnect
- **Storage**: IPFS / Pinata (if used)
- **Backend**: (If applicable, mention Node.js, Express, etc.)

## ✨ Features
- Mint NFTs with metadata stored on IPFS
- Buy and sell NFTs using ETH
- Smart contract ensures secure and trustless transactions
- Connect and interact using MetaMask
- User dashboard to track owned and listed NFTs

## 📦 Installation
### Prerequisites
- Node.js v16+
- Hardhat
- MetaMask extension
- Ethereum testnet faucet (Goerli, Sepolia, etc.)

### Clone the Repository
```sh
git clone https://github.com/yourusername/nft-marketplace.git
cd nft-marketplace
```

### Install Dependencies
```sh
npm install
```

### Compile Smart Contracts
```sh
npx hardhat compile
```

### Deploy Smart Contracts
```sh
npx hardhat run scripts/deploy.js --network goerli  # Change network if required
```

## 🎮 Usage
1. Connect MetaMask to the Ethereum testnet.
2. Deploy the contract and note the deployed address.
3. Update frontend with the contract address.
4. Run the frontend (if applicable):
   ```sh
   npm start
   ```
5. Mint, list, and trade NFTs!

## 👥 Team Members
- **Jinisha Bose** – Smart Contracts
- **Stiwart Saxena** – Frontend Development
- **Piyush Verma** – Backend & API
- **Tikesh Sahu** – UI/UX Design

## 📬 Contact
For queries, reach out to us at stiwartsaxena@gmail.comor open an issue in the repository.

---
*Developed with ❤️ for HackIndia 2025!*
