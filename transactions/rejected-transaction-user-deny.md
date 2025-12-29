### Rejected Transaction – User Denies Signature

**Objective**  
Verify correct UX and system behavior when a user rejects a transaction in the wallet.

**Preconditions**
- Wallet is connected
- User is on a supported network
- User has sufficient balance
- dApp is ready to initiate a transaction

**Steps**
1. Open dApp
2. Initiate any on-chain transaction (swap / stake / mint)
3. Wallet popup appears
4. Click **Reject / Deny** in wallet

**Expected Result**
- Transaction is not sent to blockchain
- No gas is spent
- Clear error or status message shown in UI (e.g. “Transaction rejected”)
- UI returns to a safe state
- User can retry the action manually

**Risk if Broken**
User may believe the transaction failed due to a system error and repeatedly retry, causing confusion or unintended actions.
