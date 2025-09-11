

This is a section of  Solidity .
# 🚀 Fund Me Smart Contract  

A self-made **crowdfunding smart contract** built with **Solidity** and **Foundry**.  
This project allows anyone to **fund the contract with ETH** while ensuring only the **owner can withdraw** the balance. It’s a part of my **blockchain learning journey**, where I’m exploring smart contracts, testing, and deployment with Foundry.  

---

## ✨ Features  
- 📥 **Fund Contract** → Anyone can contribute ETH.  
- 💸 **Withdraw Funds** → Only the contract owner can withdraw.  
- 🛡 **Minimum Funding Requirement** → Prevents spam/very small transactions.  
- 🧪 **Unit Tests with Foundry** → Reliable and tested contract logic.  
- ⚡ **Gas Efficient** → Written with Solidity best practices.  

---

## ⚙️ Tech Stack  
- **Solidity** → Smart contract language  
- **Foundry** → Development, testing, and deployment framework  
- **Anvil** → Local Ethereum node for simulation  
- **GitHub Actions** → Continuous integration support (optional)  

---

## 📂 Project Structure  
├── src/
│ └
── FundMe.sol # Main crowdfunding contract

├── test/
│ └── FundMe.t.sol # Unit tests for contract

├── script/
│ └── DeployFundMe.s.sol # Deployment script

└── foundry.toml # Foundry config file


## 🙌 About the Author  

👤 **Abhinav Malik**  


🔗 **Connect with me:**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abhinav%20Malik-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhinav-malik-16b493277/)  
[![GitHub](https://img.shields.io/badge/GitHub-abhinav15ab--bot-black?logo=github)](https://github.com/abhinav15ab-bot)

---

## 🚀 Getting Started  

### 1️⃣ Install Foundry  
```bash
curl -L https://foundry.paradigm.xyz | bash
foundryup
2️⃣ Clone Repo
bash
Copy code
git clone https://github.com/abhinav15ab-bot/foundry-fund-me-f25.git
cd foundry-fund-me-f25
3️⃣ Build & Test
bash
Copy code
forge build
forge test
🧑‍💻 Usage
Run a local blockchain:

bash
Copy code
anvil
Deploy the contract locally:

bash
Copy code
forge script script/DeployFundMe.s.sol --rpc-url http://127.0.0.1:8545 --private-key <YOUR_PRIVATE_KEY> --broadcast
📊 Example Test Results
csharp
Copy code
Running 4 tests for test/FundMe.t.sol
[PASS] testFundUpdatesDataStructure()
[PASS] testOwnerCanWithdraw()
[PASS] testMinimumEthRequirement()
[PASS] testOnlyOwnerCanWithdraw()


