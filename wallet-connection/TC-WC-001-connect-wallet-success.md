### Test Case ID: TC-WC-001

**Title:** Successful wallet connection via MetaMask

**Module:** Wallet Connection  
**Wallet:** MetaMask  
**Network:** Ethereum (Sepolia)  

**Priority:** High  
**Severity:** Critical  

---

### Preconditions
- MetaMask browser extension is installed
- Wallet is unlocked
- User is on dApp homepage
- Correct network (Ethereum Sepolia) is selected in MetaMask

---

### Test Steps
1. Click the "Connect Wallet" button on the dApp homepage
2. Select MetaMask from the wallet list
3. Confirm connection in the MetaMask popup

---

### Expected Result
- Wallet connection request is approved
- User wallet address is displayed in the dApp UI
- Connection status changes to "Connected"
- No error messages are shown

---

### Notes / Risk
- Verify displayed wallet address matches MetaMask account
- Incorrect connection handling may block all further user actions
