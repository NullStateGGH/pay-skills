---
name: api-ep-settlement-verify
title: "Settlement Verify — NullState"
description: "Verify a Solana USDC settlement transaction. Submit tx hash, get verified receipt with on-chain proof."
use_case: "Verify a Solana USDC settlement transaction. Submit tx hash, get verified receipt with on-chain proof."
category: payments
service_url: https://34.41.139.70:8080
openapi:
  content: |
    {"openapi":"3.1.0","info":{"title":"Settlement Verify","version":"1.0.0"},"servers":[{"url":"https://34.41.139.70:8080"}],"paths":{"/api/v1/settlement/verify":{"post":{"summary":"Settlement Verify","responses":{"200":{"description":"Success"},"402":{"description":"Payment required"}}}}}}
---

# Settlement Verify — $0.010 per call

Verify a Solana USDC settlement transaction. Submit tx hash, get verified receipt with on-chain proof.

**Method:** POST
**Path:** /api/v1/settlement/verify
**Price:** $0.010 USDC on Solana
**Auth:** Wallet-based (no signup)
**Pay.sh:** `pay skills search api-ep-settlement-verify`
