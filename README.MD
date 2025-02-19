# Fiends.me - Contract Addresses

Welcome to the official repository for **Fiends.me** contract addresses. This repository provides an up-to-date list of verified smart contract addresses deployed across multiple blockchain networks.

## 🔹 Overview

Fiends.me is building an AI-powered launchpad with **FIEND tokens**, enabling seamless AI-agent creation, management, and blockchain integration. This repository serves as a transparent and immutable record of deployed contract addresses, ensuring easy accessibility for developers, integrators, and the community.

## 📜 **Contract Addresses**

### **Base Sepolia Deployment**
| Contract       | Address                                      | Description |
|--------------|----------------------------------------------|------------|
| **FIEND Token** | `0x29b612CE8a374d57259657304594db874800830D` | ERC-20 utility token for Fiends.me |
| **Locker** | `0xC48Db190aB4Ede79B082aF2761B978C843343087` | Smart contract for token locking mechanisms |
| **AgentPool** | `0xfd270e5Ead9f19Da065814adE5C5C6FD14e0d310` | Liquidity and staking pool for AI agents |
| **AgentFactory** | `0x497Be2693b62872cCace7023eA19fF9144464366` | Factory contract for deploying AI agents |

For updates on additional deployments, check the [`/contracts`](./contracts/) directory.

---

## 🛠 **Usage & Integration**
Developers can integrate with our smart contracts using **Ethers.js**, **Web3.js**, or any blockchain SDK.

### **Example (Ethers.js)**
```javascript
import { ethers } from "ethers";

const provider = new ethers.providers.JsonRpcProvider("https://sepolia.base.org");
const contractAddress = "0x29b612CE8a374d57259657304594db874800830D";
const abi = [...];  // Insert FIEND token ABI

const fiendToken = new ethers.Contract(contractAddress, abi, provider);
console.log(await fiendToken.totalSupply());
```

---

## 📢 **Community & Contributions**
- **Join the discussion:** [Discord](#) | [Twitter](#)
- **Contribute:** Check [`CONTRIBUTING.md`](./docs/contributing.md) for guidelines.

All contributions are welcome! Please submit issues or pull requests to help improve this repository.

## ⚖️ **License**
This repository is licensed under [MIT License](./LICENSE).
