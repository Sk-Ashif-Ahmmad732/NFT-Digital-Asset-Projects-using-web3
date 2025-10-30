# 🎨 Simple NFT Marketplace on Celo

A beginner-friendly NFT marketplace smart contract built on the Celo blockchain, enabling artists and creators to mint, list, and trade digital assets using Celo's stablecoins (cUSD/cEUR) for predictable pricing.

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/75dbb0f1-543e-4e14-a1a8-7e77b326b12d" />

## 🌟 Overview

This project provides a simple yet powerful NFT marketplace specifically designed for the Celo ecosystem. It leverages Celo's EVM compatibility and focuses on real-world usability by supporting stablecoin transactions, making it ideal for local artists and creators who want predictable pricing without crypto volatility.

## 🚀 What It Does

The Simple NFT Marketplace allows users to:

- **Mint NFTs**: Create unique digital assets with custom metadata (IPFS links, descriptions, etc.)
- **List for Sale**: Set prices in Celo-native currencies (CELO, cUSD, or cEUR)
- **Buy NFTs**: Purchase listed NFTs with automatic ownership transfer
- **Manage Listings**: Unlist NFTs from the marketplace at any time
- **Track Ownership**: View complete NFT details including creator, owner, and sale status

## ✨ Features

### 🎯 Core Functionality
- **Simple Minting**: Anyone can create NFTs with metadata links
- **Flexible Pricing**: Support for Celo's native tokens and stablecoins
- **Secure Transfers**: Built-in ownership validation and payment handling
- **Event Logging**: Complete transaction history via blockchain events
- **Excess Refunds**: Automatic refund of overpayment to buyers

### 🔒 Security Features
- Owner-only listing controls
- Sale status verification
- Payment amount validation
- Self-purchase prevention
- Secure fund transfers

### 💡 Beginner-Friendly
- No external dependencies
- Clean, commented code
- Simple data structures
- Easy to understand and modify
- Ready to deploy without configuration

## 📋 Smart Contract Details

### Deployed Contract
**Network**: Celo Sepolia Testnet  
**Contract Address**: [`0x23b0267Cf57887aB624055f607b70C6dc6A93A62`](https://celo-sepolia.blockscout.com/address/0x23b0267Cf57887aB624055f607b70C6dc6A93A62)

### Main Functions

| Function | Description |
|----------|-------------|
| `mintNFT(string memory _metadata)` | Create a new NFT with metadata |
| `listNFT(uint256 _tokenId, uint256 _price)` | List an NFT for sale at a specific price |
| `buyNFT(uint256 _tokenId)` | Purchase a listed NFT |
| `unlistNFT(uint256 _tokenId)` | Remove an NFT from sale |
| `getNFT(uint256 _tokenId)` | View complete NFT details |
| `getTotalNFTs()` | Get total number of minted NFTs |

## 🛠️ Technology Stack

- **Language**: Solidity ^0.8.0
- **Blockchain**: Celo (EVM-compatible)
- **Standard**: Custom NFT implementation
- **Network**: Celo Sepolia Testnet

## 📦 Getting Started

### Prerequisites
- MetaMask or compatible Web3 wallet
- Celo Sepolia testnet configured
- Test CELO tokens (get from [Celo Faucet](https://faucet.celo.org/alfajores))

### Interacting with the Contract

1. **Connect to Celo Sepolia**
   - Network Name: Celo Sepolia
   - RPC URL: `https://alfajores-forno.celo-testnet.org`
   - Chain ID: `44787`
   - Currency Symbol: `CELO`

2. **Visit the Contract**
   - Go to [BlockScout](https://celo-sepolia.blockscout.com/address/0x23b0267Cf57887aB624055f607b70C6dc6A93A62)
   - Use the "Write Contract" tab to interact

3. **Mint Your First NFT**
   ```solidity
   mintNFT("ipfs://your-metadata-hash")
   ```

4. **List for Sale**
   ```solidity
   listNFT(1, 1000000000000000000) // 1 CELO
   ```




## 🎯 Use Cases

- **Local Artist Marketplace**: Enable artists to sell digital art with stable pricing
- **Creator Economy**: Support content creators with NFT-based monetization
- **Digital Collectibles**: Create and trade unique digital items
- **Learning Project**: Perfect for understanding NFT mechanics and Solidity basics

## 🔮 Future Enhancements

- [ ] Integration with ERC-721 standard
- [ ] Royalty payment system for creators
- [ ] Batch minting functionality
- [ ] Direct cUSD/cEUR token integration
- [ ] Frontend marketplace interface
- [ ] IPFS metadata storage
- [ ] Auction functionality

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Resources

- [Celo Documentation](https://docs.celo.org/)
- [Celo Faucet](https://faucet.celo.org/alfajores)
- [Solidity Documentation](https://docs.soliditylang.org/)
- [BlockScout Explorer](https://celo-sepolia.blockscout.com/)

## 📞 Support

For questions or support, please open an issue in this repository.

---

⭐ **Star this repo if you find it helpful!**

# Built with ❤️ for the Celo community by Sk Ashif Ahmmad

