# 🏃 SpeedRunEthereum Challenges

> My journey through the SpeedRunEthereum challenges - learning to build on Ethereum one challenge at a time.

## 📚 About This Repository

This repository contains my solutions and implementations for the [SpeedRunEthereum](https://speedrunethereum.com) challenges. Each challenge is a hands-on project designed to teach core Ethereum development concepts, from basic smart contracts to advanced DeFi protocols.

## 🎯 Completed Challenges

### ✅ Challenge 1: Tokenization

**Status:** Completed ✓

Build and deploy an ERC-721 NFT collection with metadata stored on IPFS. Learn about non-fungible tokens, onchain ownership, and how to create a full-stack Web3 application.

- **Live Demo:** [https://challenge-tokenization-bdf24ha4n-olirahetaxs-projects.vercel.app](https://challenge-tokenization-bdf24ha4n-olirahetaxs-projects.vercel.app)
- **Contract (Sepolia):** [0x38e98A76FAD276e41E325E911d1c6a89Aeebbff2](https://sepolia.etherscan.io/address/0x38e98A76FAD276e41E325E911d1c6a89Aeebbff2)
- **Folder:** [`/challenge-tokenization`](./challenge-tokenization)

**Key Learnings:**

- ERC-721 NFT standard implementation
- Smart contract deployment to testnets
- IPFS for decentralized metadata storage
- Frontend integration with Web3 wallets
- Gas optimization and transaction management

---

### ✅ Challenge 2: Decentralized Staking

**Status:** Completed ✓

Build a decentralized staking application where users can stake ETH to reach a funding goal within a deadline. Learn about payable functions, time-based logic, and contract-to-contract interactions.

- **Live Demo:** [https://challenge-centralized-staking-ixvmr9vvw-olirahetaxs-projects.vercel.app](https://challenge-centralized-staking-ixvmr9vvw-olirahetaxs-projects.vercel.app)
- **Staker Contract (Sepolia):** [0x0C270E5bbb85696F0D3Ac7DAE88c115204709186](https://sepolia.etherscan.io/address/0x0C270E5bbb85696F0D3Ac7DAE88c115204709186)
- **ExampleExternalContract (Sepolia):** [0xd547c429Ee4C23c5D6558bd2F29414A57c9B38E2](https://sepolia.etherscan.io/address/0xd547c429Ee4C23c5D6558bd2F29414A57c9B38E2)
- **Folder:** [`/challenge-decentralized-staking`](./challenge-decentralized-staking)

**Key Learnings:**

- Payable functions and receiving ETH in contracts
- Time-based logic with `block.timestamp` and deadlines
- Contract-to-contract interactions
- Event emission and indexing for frontend
- Withdrawal patterns and reentrancy protection
- Custom modifiers for access control
- `receive()` fallback function implementation

---
