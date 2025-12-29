### Test Case ID: TC-TX-004

**Title:** High gas fee warning before transaction

**Module:** Transactions  
**Platform:** Web (Desktop Browser)  
**Wallet:** MetaMask  
**Network:** Ethereum (Sepolia)  

**Priority:** Medium  
**Severity:** Major  

---

### Preconditions
- MetaMask installed and unlocked  
- User is connected to dApp  
- User has sufficient ETH and tokens  

---

### Test Steps
1. Navigate to "Send Tokens" section  
2. Enter recipient and amount  
3. Click "Send"  
4. Observe gas fee displayed in MetaMask popup  

---

### Expected Result
- If gas fee exceeds threshold, dApp warns user  
- User can choose to confirm or cancel  
- Transaction proceeds only with confirmation  

---

### Notes / Risk
- Failure to warn may lead to unexpected high fees  
- UX impact on trust and retention
