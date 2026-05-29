---
name: api-ep-transaction-history
title: "Transaction History — NullState"
description: "Get settlement transaction history for any agent."
use_case: "Get settlement transaction history for any agent."
category: data
service_url: https://34.41.139.70:8080
openapi:
  content: |
    {"openapi":"3.1.0","info":{"title":"Transaction History","version":"1.0.0"},"servers":[{"url":"https://34.41.139.70:8080"}],"paths":{"/api/v1/transaction/history":{"get":{"summary":"Transaction History","responses":{"200":{"description":"Success"},"402":{"description":"Payment required"}}}}}}
---

# Transaction History — $0.005 per call

Get settlement transaction history for any agent.

**Method:** GET
**Path:** /api/v1/transaction/history
**Price:** $0.005 USDC on Solana
**Auth:** Wallet-based (no signup)
**Pay.sh:** `pay skills search api-ep-transaction-history`
