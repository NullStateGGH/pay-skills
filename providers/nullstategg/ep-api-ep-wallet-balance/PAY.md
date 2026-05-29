---
name: api-ep-wallet-balance
title: "Wallet Balance — NullState"
description: "Check on-chain USDC/SOL balance of any Solana wallet address."
use_case: "Check on-chain USDC/SOL balance of any Solana wallet address."
category: data
service_url: https://34.41.139.70:8080
openapi:
  content: |
    {"openapi":"3.1.0","info":{"title":"Wallet Balance","version":"1.0.0"},"servers":[{"url":"https://34.41.139.70:8080"}],"paths":{"/api/v1/wallet/balance":{"get":{"summary":"Wallet Balance","responses":{"200":{"description":"Success"},"402":{"description":"Payment required"}}}}}}
---

# Wallet Balance — $0.001 per call

Check on-chain USDC/SOL balance of any Solana wallet address.

**Method:** GET
**Path:** /api/v1/wallet/balance
**Price:** $0.001 USDC on Solana
**Auth:** Wallet-based (no signup)
**Pay.sh:** `pay skills search api-ep-wallet-balance`
