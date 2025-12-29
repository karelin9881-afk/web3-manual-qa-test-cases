### Test Case ID: TC-TX-006

**Title:** User closes MetaMask popup before confirmation

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

---

### Test Steps
1. Navigate to "Send Tokens" section  
2. Enter recipient and amount  
3. Click "Send"  
4. Close MetaMask popup without confirming  

---

### Expected Result
- Transaction is cancelled  
- Wallet balance unchanged  
- dApp remains responsive  
- User sees clear message: "Transaction cancelled"  

---

### Notes / Risk
- Failure to handle popup closure may lock dApp UI  
- UX impact: user frustration and trust issues
