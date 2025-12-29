### Test Case ID: TC-WC-003

**Title:** Switch wallet account after successful connection

**Module:** Wallet Connection  
**Platform:** Web (Desktop Browser)
**Wallet:** MetaMask  
**Network:** Ethereum (Sepolia)  

**Priority:** High  
**Severity:** Critical  

---

### Preconditions
- MetaMask browser extension is installed
- Wallet is unlocked
- User is connected to the dApp
- Account A is currently connected

---

### Test Steps
1. Open MetaMask extension
2. Switch from Account A to Account B
3. Return to the dApp

---

### Expected Result
- dApp detects account change automatically
- Displayed wallet address updates to Account B
- No page reload is required
- No error messages are shown

---

### Notes / Risk
- Incorrect account handling may lead to actions from the wrong wallet
- This can cause direct user fund loss
