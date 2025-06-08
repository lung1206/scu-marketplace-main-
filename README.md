# 🧾 SCU NFT Marketplace

A full-stack decentralized application (DApp) that enables users to list, update, revoke, and purchase NFTs on the Ethereum Sepolia testnet. Built with React and Web3.js, and powered by smart contracts written in Solidity.

---

## 📌 Project Overview

This NFT Marketplace allows users to:
- Connect their wallet via MetaMask
- List their own NFTs for sale
- Update or cancel their listings
- Browse and purchase NFTs listed by others

The marketplace interacts directly with a deployed ERC-721 compatible smart contract without relying on centralized servers or third-party services.

---

## 🧩 Main Features

| Feature         | Description                                             |
|----------------|---------------------------------------------------------|
| 🎨 List NFT     | List owned NFTs for sale at a custom price              |
| 💰 Buy NFT      | Buy NFTs listed by other users                          |
| 🔁 Update Price | Update the price of an already listed NFT               |
| ❌ Revoke NFT   | Cancel a listed NFT before it's sold                    |
| 🧾 View Listings| Display all active listings on the frontend             |
| 🔗 Wallet Connect | Connect to MetaMask using Web3.js                    |

---
## 🧱 Tech Stack

| Layer          | Technology               |
| -------------- | ------------------------ |
| Frontend       | React.js                 |
| Blockchain     | Ethereum Sepolia Testnet |
| Wallet         | MetaMask                 |
| Web3 Library   | Web3.js                  |
| Smart Contract | Solidity (ERC-721)       |

---

## 📂 Directory Highlights 

📁 WalletConnect/
- WalletConnect.js      // Handles MetaMask login
  
📁 NFTManagement/
- NFTList.js            // Shows listed NFTs
- ListNFT.js            // Lists a new NFT
- RevokeNFT.js          // Cancels a listing
- UpdateNFT.js          // Updates listing price
- BuyNFT.js             // Purchases an NFT

📁 contracts/
- Marketplace.sol       // Main smart contract
- NFT.sol               // Example ERC721 token

 ---
 # Contract Address

- NFTSwap address: 0xECdeAaD85A695CEb83d5d9e00c0D3160220773A7
  
  NFTMarketplace contract

- ERC721 address: 0x49B2d6D7C118ebb606D1402797c9a9d183beA706
  
  NFTs for testing
---
## 🧪 Deployment Notes
✅ Smart contract deployed to Sepolia Testnet

🦊 MetaMask must be connected to Sepolia network

📤 Deployment and verification done via Remix

---
#  Interface Overview

![3](https://github.com/user-attachments/assets/6c90fc95-5612-4a9c-aaf0-2a3c06fcb329)
![2](https://github.com/user-attachments/assets/79859ee7-5ca1-45ce-b990-92b14412968f)
![1](https://github.com/user-attachments/assets/72001bb7-7152-4217-a0f8-28a49a516428)

