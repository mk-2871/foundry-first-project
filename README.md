# 🚀 Foundry First Project

A beginner-friendly Ethereum smart contract project using [Foundry](https://book.getfoundry.sh/), a blazing fast toolkit for Solidity development.

---

## 🧰 Tools & Technologies

- **Foundry**: Modular toolkit for Ethereum app development  
- **Forge**: Build and test smart contracts  
- **Cast**: CLI for contract interaction  
- **Anvil**: Local Ethereum node  
- **Chisel**: Solidity REPL  

---

## 📦 Installation

### 1. Install Foundry

```bash
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

### 2. Clone the Repository
```
git clone https://github.com/mk-2871/foundry-first-project.git
cd foundry-first-project

```

🛠️ Usage
🔨 Build Contracts
```
forge build

```

✅ Run Tests
```
forge test

```
🚀 Deploy Contracts
Copy
Edit
```
forge deploy
```

🧪 Interact with Deployed Contracts

```
cast call <contract_address> <function_signature>

```

Example:
```
cast call 0x123...abc "balanceOf(address)" 0xabc...123

```

📁 Project Structure (Basic)
```

foundry-first-project/
├── src/                  # Solidity contracts
├── test/                 # Test files
├── script/               # Deployment scripts
├── foundry.toml          # Project config


```

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to fork the repo and submit a pull request.

📄 License
This project is licensed under the MIT License.
See the LICENSE file for more details.


