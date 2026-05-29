---
name: api-ep-proof-generate
title: "Settlement Proof — NullState"
description: "Generate cryptographic proof of settlement for dispute resolution."
use_case: "Generate cryptographic proof of settlement for dispute resolution."
category: payments
service_url: https://34.41.139.70:8080
openapi:
  content: |
    {"openapi":"3.1.0","info":{"title":"Settlement Proof","version":"1.0.0"},"servers":[{"url":"https://34.41.139.70:8080"}],"paths":{"/api/v1/proof/generate":{"post":{"summary":"Settlement Proof","responses":{"200":{"description":"Success"},"402":{"description":"Payment required"}}}}}}
---

# Settlement Proof — $0.020 per call

Generate cryptographic proof of settlement for dispute resolution.

**Method:** POST
**Path:** /api/v1/proof/generate
**Price:** $0.020 USDC on Solana
**Auth:** Wallet-based (no signup)
**Pay.sh:** `pay skills search api-ep-proof-generate`
