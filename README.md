# Hey, I'm Moebium 👋

### Smart Contract Developer | Building on Ethereum | 🇮🇩 Indonesia

I'm a Solidity developer focused on writing **secure, well-tested smart contracts** for DeFi and DApp projects. Currently deepening my skills in contract security, testing patterns, and DApp development.

---

## 🔨 What I Build

- **Smart Contracts** — ERC-20 tokens, staking protocols, access-controlled systems
- **Security-First Code** — ReentrancyGuard, Checks-Effects-Interactions, OpenZeppelin standards
- **DApps** — On-chain logic connected to frontend interfaces

---

## 🛠️ Stack

| | Tools |
|---|---|
| **Language** | Solidity |
| **Security** | OpenZeppelin, ReentrancyGuard, Ownable |
| **Testing** | Foundry |
| **IDE** | Remix IDE, VS Code |
| **Network** | Ethereum (Sepolia Testnet) |
| **Currently Learning** | Hardhat, ethers.js, ERC-721 |

---

## 📁 Projects

### 🏦 [ProBank — Secure Digital Bank Contract](https://github.com/Moebium/MyFirstSmartContract)
A smart contract bank with full security implementation.

**What it does:**
- Users deposit and withdraw ETH
- Owner-only bank balance visibility
- Protected against reentrancy attacks

**Security used:**
- ✅ `ReentrancyGuard` from OpenZeppelin
- ✅ Checks-Effects-Interactions pattern
- ✅ `Ownable` access control
- ✅ `private` balance mapping

> Deployed & tested on Sepolia Testnet

---

### 🪙 [Kareka Token (KRK) — ERC-20 Token](https://github.com/Moebium/Kareka-Token-Contract)
A fully functional ERC-20 token deployed on Ethereum Sepolia Testnet.

**What it does:**
- Standard ERC-20 token compatible with MetaMask & all wallets
- Fixed supply of 1,000,000 KRK
- Owner-controlled minting

**Built with:**
- ✅ OpenZeppelin ERC-20 standard
- ✅ `Ownable` for admin control
- ✅ Live contract on Sepolia: `0xF95a8A5ba4eDf4356bC373f272b71F2AfB1bC8A4`

> Importable directly into MetaMask on Sepolia network

---

### 🏧 [StakingDapp — DeFi Staking Contract](https://github.com/Moebium/StakingDapp)
A secure DeFi staking protocol built with Solidity.

**What it does:**
- Users stake ETH and earn 10% reward
- 30-day lock period enforced on-chain
- Secure reward claiming system

**Built with:**
- ✅ Checks-Effects-Interactions security pattern
- ✅ Custom modifiers for access control
- ✅ Time-based lock period using `block.timestamp`
- ✅ Struct-based user data storage

---

### 🧪 [StakingDapp-Tests — Foundry Test Suite](https://github.com/Moebium/StakingDapp-Tests)
Complete Foundry test suite for the StakingDapp contract.

**8 tests — all passing ✅**
- Happy path tests (stake, unstake, claim reward)
- Revert tests (zero amount, stake twice, unstake early)
- Time-based tests using `vm.warp()`
- Balance verification tests

**Built with:**
- ✅ Foundry framework
- ✅ Cheat codes: vm.prank, vm.warp, vm.deal, vm.expectRevert
- ✅ Test results documented in test-results.txt

---

## 📚 Currently Learning

- [x] ERC-20 token standard ✅ done with Kareka Token!
- [x] DeFi patterns: staking, rewards, time locks ✅ done with StakingDapp!
- [x] Foundry testing framework ✅ done with StakingDapp-Tests!
- [ ] Hardhat — local testing & deployment
- [ ] ethers.js — connecting contracts to frontend
- [ ] ERC-721 NFT standard

---

## 🌍 Open To

- Remote Junior Smart Contract Developer roles
- Freelance Solidity work
- Bounty contributions (Gitcoin, Immunefi)
- Open source collaboration

📍 Based in Semarang, Indonesia — available globally, async-friendly

---

## 📬 Contact

- GitHub: [@Moebium](https://github.com/Moebium)
- Open to work: **Yes**

---

*"Every line of code that holds real money must be written like someone is trying to break it."*
