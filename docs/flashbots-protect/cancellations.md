---
title: Cancellations
---

Transactions submitted to Flashbots Protect are directed to the Flashbots MEV-Share node and may remain pending for up to 6 minutes.

Flashbots Protect provides the functionality to cancel pending transactions. A cancellation transaction must be submitted to Flashbots Protect to cancel a pending transaction and adhere to the following criteria:

- The cancellation transaction must be submitted from the **same address** as the original pending transaction.
- The cancellation transaction should have the **same nonce** as the original pending transaction.
- The **from and to addresses** should match the original transactionʻs.
- The **data field** of the cancellation transaction should be left empty.

## No cost to cancel

The cancellation transaction is to verify that you have control over the account that initiated the pending transaction. The cancellation transaction is not included on-chain and incurs no cost. 
