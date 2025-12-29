### Test Case ID: TC-TX-003

**Title:** Transaction fails due to insufficient funds

**Module:** Transactions  
**Platform:** Web (Desktop Browser)  
**Wallet:** MetaMask  
**Network:** Ethereum (Sepolia)  

**Priority:** High  
**Severity:** Critical  

---

### Preconditions
- MetaMask installed and unlocked  
- User is connected to dApp  
- User does NOT have enough ETH for gas OR not enough tokens  

---

### Test Steps
1. Navigate to "Send Tokens" section in the dApp  
2. Enter recipient address and amount exceeding balance  
3. Click "Send"  
4. Confirm transaction in MetaMask popup  

---

### Expected Result
- Transaction is rejected  
- Wallet balance remains unchanged  
- dApp displays clear error (e.g., "Insufficient funds")  
- No other functionality broken  

---

### Notes / Risk
- Missing validation may allow user to attempt failed transactions repeatedly  
- UX must prevent user frustration
