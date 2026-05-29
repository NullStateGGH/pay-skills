---
name: api-ep-network-status
title: "Network Status — NullState"
description: "Check Solana network health and latest confirmed slot."
use_case: "Check Solana network health and latest confirmed slot."
category: data
service_url: https://34.41.139.70:8080
openapi:
  content: |
    {"openapi":"3.1.0","info":{"title":"Network Status","version":"1.0.0"},"servers":[{"url":"https://34.41.139.70:8080"}],"paths":{"/api/v1/network/status":{"get":{"summary":"Network Status","responses":{"200":{"description":"Success"},"402":{"description":"Payment required"}}}}}}
---

# Network Status — $0.001 per call

Check Solana network health and latest confirmed slot.

**Method:** GET
**Path:** /api/v1/network/status
**Price:** $0.001 USDC on Solana
**Auth:** Wallet-based (no signup)
**Pay.sh:** `pay skills search api-ep-network-status`
