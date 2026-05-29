---
name: api-ep-settlement-receipt
title: "Settlement Receipt — NullState"
description: "Generate a signed settlement receipt for audit trails and dispute resolution."
use_case: "Generate a signed settlement receipt for audit trails and dispute resolution."
category: payments
service_url: https://34.41.139.70:8080
openapi:
  content: |
    {"openapi":"3.1.0","info":{"title":"Settlement Receipt","version":"1.0.0"},"servers":[{"url":"https://34.41.139.70:8080"}],"paths":{"/api/v1/settlement/receipt":{"post":{"summary":"Settlement Receipt","responses":{"200":{"description":"Success"},"402":{"description":"Payment required"}}}}}}
---

# Settlement Receipt — $0.010 per call

Generate a signed settlement receipt for audit trails and dispute resolution.

**Method:** POST
**Path:** /api/v1/settlement/receipt
**Price:** $0.010 USDC on Solana
**Auth:** Wallet-based (no signup)
**Pay.sh:** `pay skills search api-ep-settlement-receipt`
