---
name: api-ep-credits-balance
title: "Credit Balance — NullState"
description: "Check prepaid USDC credit balance for any agent wallet."
use_case: "Check prepaid USDC credit balance for any agent wallet."
category: payments
service_url: https://34.41.139.70:8080
openapi:
  content: |
    {"openapi":"3.1.0","info":{"title":"Credit Balance","version":"1.0.0"},"servers":[{"url":"https://34.41.139.70:8080"}],"paths":{"/api/v1/credits/balance":{"get":{"summary":"Credit Balance","responses":{"200":{"description":"Success"},"402":{"description":"Payment required"}}}}}}
---

# Credit Balance — $0.005 per call

Check prepaid USDC credit balance for any agent wallet.

**Method:** GET
**Path:** /api/v1/credits/balance
**Price:** $0.005 USDC on Solana
**Auth:** Wallet-based (no signup)
**Pay.sh:** `pay skills search api-ep-credits-balance`
