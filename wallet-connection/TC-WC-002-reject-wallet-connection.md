### Test Case ID: TC-WC-002

**Title:** Reject wallet connection request in MetaMask

**Module:** Wallet Connection  
**Wallet:** MetaMask  
**Network:** Ethereum (Sepolia)  

**Priority:** High  
**Severity:** Major  

---

### Preconditions
- MetaMask browser extension is installed
- Wallet is unlocked
- User is on dApp homepage

---

### Test Steps
1. Click the "Connect Wallet" button on the dApp homepage
2. Select MetaMask from the wallet list
3. Click "Reject" in the MetaMask connection popup

---

### Expected Result
- Wallet connection is not established
- User remains in a disconnected state
- No wallet address is displayed
- Clear and user-friendly message is shown (e.g. "Connection rejected")
- dApp remains usable without page reload

---

### Notes / Risk
- Missing or unclear rejection handling may confuse users
- Poor UX here often leads to user drop-off
