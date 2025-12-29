### Test Case ID: TC-TX-005

**Title:** Transaction reverted by smart contract

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
- Transaction will violate smart contract rules  

---

### Test Steps
1. Navigate to "Send Tokens" section  
2. Enter recipient and amount violating contract rules  
3. Click "Send"  
4. Confirm transaction in MetaMask popup  

---

### Expected Result
- Transaction is reverted  
- Wallet balance remains unchanged  
- dApp displays clear error message from blockchain  
- No other functionality broken  

---

### Notes / Risk
- Proper handling avoids user confusion and potential loss  
- Verifying smart contract error messages is important
