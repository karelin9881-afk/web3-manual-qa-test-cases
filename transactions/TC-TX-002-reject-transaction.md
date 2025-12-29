### Test Case ID: TC-TX-002

**Title:** Reject token transfer transaction in MetaMask

**Module:** Transactions  
**Platform:** Web (Desktop Browser)  
**Wallet:** MetaMask  
**Network:** Ethereum (Sepolia)  

**Priority:** High  
**Severity:** Major  

---

### Preconditions
- MetaMask installed and unlocked  
- User is connected to dApp  
- User has sufficient tokens  

---

### Test Steps
1. Navigate to "Send Tokens" section in the dApp  
2. Enter recipient address and amount  
3. Click "Send"  
4. Click "Reject" in MetaMask popup  

---

### Expected Result
- Transaction is not submitted  
- Wallet balance remains unchanged  
- dApp displays "Transaction rejected" or equivalent message  
- No errors in UI  

---

### Notes / Risk
- Incorrect rejection handling may confuse users  
- UX must clearly indicate transaction did not happen
