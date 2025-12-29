### Test Case ID: TC-TX-001

**Title:** Successful token transfer transaction

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
- User has sufficient ETH for gas  
- User has sufficient tokens for transfer

---

### Test Steps
1. Navigate to "Send Tokens" section in the dApp  
2. Enter recipient address  
3. Enter amount of tokens to send  
4. Click "Send"  
5. Confirm transaction in MetaMask popup

---

### Expected Result
- Transaction is successfully submitted  
- Transaction status is updated in dApp UI  
- Wallet balance decreases accordingly  
- Tokens received by recipient  
- No error messages displayed

---

### Notes / Risk
- Incorrect handling may cause duplicate or failed transactions  
- High gas fees must be displayed correctly  
- Verify transaction hash in Etherscan (optional)
