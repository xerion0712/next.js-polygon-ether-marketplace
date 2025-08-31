# Next.js Ethereum & Polygon NFT Marketplace

A decentralized marketplace built with **Next.js**, **Hardhat**, and **Polygon/Ethereum**, allowing users to **mint, buy, and sell NFTs** seamlessly.

##  Features

* NFT Minting on Ethereum & Polygon
* Buy/Sell NFTs with MetaMask integration
* TailwindCSS UI for a clean, responsive design
* Hardhat for contract deployment & testing
* Supports multiple RPC endpoints

##  Tech Stack

* **Frontend:** Next.js, React, TailwindCSS
* **Smart Contracts:** Solidity, Hardhat
* **Blockchain:** Ethereum & Polygon (Matic)
* **Wallet:** MetaMask / WalletConnect

##  Project Structure

```
contracts/      → Solidity smart contracts  
pages/          → Next.js pages & routes  
public/         → Static assets  
scripts/        → Hardhat deployment scripts  
styles/         → TailwindCSS styles  
test/           → Contract tests  
```

##  Setup & Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/nextjs-eth-polygon-nft-marketplace.git
   ```
2. Install dependencies:

   ```bash
   yarn install
   ```
3. Configure environment variables:

   ```bash
   cp .example.env .env
   ```
4. Deploy smart contracts:

   ```bash
   npx hardhat run scripts/deploy.js --network mumbai
   ```
5. Start development server:

   ```bash
   yarn dev
   ```

