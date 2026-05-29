---
name: api-ep-ledger-summary
title: "Ledger Summary — NullState"
description: "Get a summary of all ledger activity and balances."
use_case: "Get a summary of all ledger activity and balances."
category: data
service_url: https://34.41.139.70:8080
openapi:
  content: |
    {"openapi":"3.1.0","info":{"title":"Ledger Summary","version":"1.0.0"},"servers":[{"url":"https://34.41.139.70:8080"}],"paths":{"/api/v1/ledger/summary":{"get":{"summary":"Ledger Summary","responses":{"200":{"description":"Success"},"402":{"description":"Payment required"}}}}}}
---

# Ledger Summary — $0.005 per call

Get a summary of all ledger activity and balances.

**Method:** GET
**Path:** /api/v1/ledger/summary
**Price:** $0.005 USDC on Solana
**Auth:** Wallet-based (no signup)
**Pay.sh:** `pay skills search api-ep-ledger-summary`
