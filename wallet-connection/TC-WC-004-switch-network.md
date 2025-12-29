### Test Case ID: TC-WC-004

**Title:** Switch network after wallet connection

**Module:** Wallet Connection  
**Wallet:** MetaMask  
**Network:** Ethereum (Sepolia → Mainnet)  

**Priority:** High  
**Severity:** Critical  

---

### Preconditions
- MetaMask browser extension is installed
- Wallet is unlocked
- User is connected to the dApp on Ethereum Sepolia

---

### Test Steps
1. Open MetaMask extension
2. Switch network from Ethereum Sepolia to Ethereum Mainnet
3. Return to the dApp

---

### Expected Result
- dApp detects network change automatically
- User is prompted to switch back to the supported network  
  **OR**
- dApp disables actions until the correct network is selected
- Clear and informative message is displayed

---

### Notes / Risk
- Performing transactions on the wrong network may lead to fund loss
- Missing network validation is a critical Web3 issue
