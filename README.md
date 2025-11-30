# 🏃 SpeedRunEthereum Challenges

> My journey through the SpeedRunEthereum challenges - learning to build on Ethereum one challenge at a time.

## 📚 About This Repository

This repository contains my solutions and implementations for the [SpeedRunEthereum](https://speedrunethereum.com) challenges. Each challenge is a hands-on project designed to teach core Ethereum development concepts, from basic smart contracts to advanced DeFi protocols.

## 📑 Table of Contents

1. [✅ Challenge 1: Tokenization](#-challenge-1-tokenization) - ERC-721 NFTs & IPFS
2. [✅ Challenge 2: Decentralized Staking](#-challenge-2-decentralized-staking) - Staking & Time-based Logic
3. [✅ Challenge 3: Token Vendor](#-challenge-3-token-vendor) - ERC-20 Token Economics
4. [✅ Challenge 4: Dice Game](#-challenge-4-dice-game) - Randomness Vulnerabilities & Exploits

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

### ✅ Challenge 3: Token Vendor

**Status:** Completed ✓

Build a token vendor that allows users to buy and sell ERC-20 tokens with ETH. Learn about token economics, automated market mechanics, and contract ownership patterns.

- **Live Demo:** [https://challenge-token-vendor-798c8gy3u-olirahetaxs-projects.vercel.app](https://challenge-token-vendor-798c8gy3u-olirahetaxs-projects.vercel.app)
- **Vendor Contract (Sepolia):** [0x9792AfBB6bc83c257aebC7Cd3A23D0E6a1eB5581](https://sepolia.etherscan.io/address/0x9792AfBB6bc83c257aebC7Cd3A23D0E6a1eB5581)
- **YourToken Contract (Sepolia):** [0x6Bb96057CaC470cF38059dF911385CF47072bA37](https://sepolia.etherscan.io/address/0x6Bb96057CaC470cF38059dF911385CF47072bA37)
- **Folder:** [`/challenge-token-vendor`](./challenge-token-vendor)

**Key Learnings:**

- ERC-20 token implementation and interactions
- Token buying/selling mechanisms with fixed pricing
- `transfer()` vs `transferFrom()` for token transfers
- Owner privileges with OpenZeppelin's `Ownable`
- Reentrancy protection with `ReentrancyGuard`
- ETH transfer best practices using `call()` instead of `transfer()`
- Event emission for buy/sell tracking
- Token allowance and approval patterns
- Contract liquidity management

---

### ✅ Challenge 4: Dice Game

**Status:** Completed ✓

Exploit the weakness of using block hash for randomness in smart contracts. Build a "rigged" contract that predicts the outcome of dice rolls and only plays when guaranteed to win. Learn about blockchain randomness, security vulnerabilities, and contract-to-contract calls.

- **Live Demo:** [https://challenge-dice-game-nine.vercel.app](https://challenge-dice-game-nine.vercel.app)
- **DiceGame Contract (Sepolia):** [0x1040B29616B5f7012895D63afabb79f418057c23](https://sepolia.etherscan.io/address/0x1040B29616B5f7012895D63afabb79f418057c23)
- **RiggedRoll Contract (Sepolia):** [0x679447e42dF751AA67F57695D3F272dBbBb41B01](https://sepolia.etherscan.io/address/0x679447e42dF751AA67F57695D3F272dBbBb41B01)
- **Folder:** [`/challenge-dice-game`](./challenge-dice-game)

**Key Learnings:**

- Understanding blockchain randomness vulnerabilities
- Block hash (`blockhash()`) limitations and predictability
- Exploiting deterministic randomness in smart contracts
- Contract-to-contract function calls with value transfer
- Using `revert()` vs `return` for transaction control
- Implementing attack/exploit contracts for security testing
- `console.log()` debugging in Hardhat for development
- Owner-only functions with OpenZeppelin's `Ownable`
- Why stronger randomness solutions (VRF, oracles) are needed
- Security implications of public blockchain data

---
