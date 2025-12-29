# Web3 Manual QA Test Cases

This repository contains **manual test cases for Web3 dApps**, focused on **wallet connections, transaction flows, and user-funds risk scenarios**.  
All test cases are written with **realistic scenarios** and **negative cases** to simulate potential user and network issues.

---

## 📌 Scope

- **Wallet Connection**
  - Connect / Disconnect Wallet (MetaMask)
  - Reject connection
  - Switch account
  - Switch network
  - Handle locked or missing wallet

- **Transactions**
  - Successful token transfers
  - Reject transaction
  - Insufficient funds
  - High gas fee warning
  - Transaction reverted by smart contract
  - User closes MetaMask popup

---

## ⚡ Why this matters

In Web3, **UX bugs can directly result in user fund loss**.  
This repository focuses on **high-risk user actions** rather than only happy paths.  
It demonstrates understanding of:

- Wallet & network interactions (MetaMask / Ethereum)
- Transaction lifecycle
- User error & rejection handling
- Edge-case scenarios common in dApps

---

## 🛠 Tools & Environment

- **Wallet:** MetaMask  
- **Platform:** Web (Desktop Browser)  
- **Network:** Ethereum Sepolia (testnet)  
- **Testing type:** Manual QA  

---

## 📁 Structure

web3-manual-qa-test-cases/
├─ wallet-connection/ # Wallet connection flows
├─ transactions/ # Transaction lifecycle & failure scenarios
└─ README.md # This file

---

## ✅ How to Use

1. Open the folder corresponding to the module you want to test (`wallet-connection` or `transactions`)  
2. Pick a test case (`TC-XXX-YYY.md`)  
3. Follow **Preconditions → Steps → Expected Results → Notes / Risk**  

All test cases follow a **consistent template** for readability and reproducibility.

---

## 💡 Highlights

- Focus on **negative and edge cases** (rejects, insufficient funds, high gas fees, network changes)  
- Shows **professional Web3 QA thinking**  
- Can be **used as a portfolio** for recruiters or leads  

---

## 📌 Next Steps (Optional for Enhancement)

- Add **mobile wallet scenarios** (MetaMask Mobile, Trust Wallet, WalletConnect)  
- Automate test cases using **Playwright / Cypress with Web3 plugin**  
- Include **screenshot or video evidence** for each scenario  
- Expand coverage to **other networks** (BSC, Polygon, Avalanche)
