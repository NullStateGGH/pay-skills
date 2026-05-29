---
name: api-ep-compliance-check
title: "Compliance Check — NullState"
description: "Validate an x402 settlement against compliance and AML rules."
use_case: "Validate an x402 settlement against compliance and AML rules."
category: identity
service_url: https://34.41.139.70:8080
openapi:
  content: |
    {"openapi":"3.1.0","info":{"title":"Compliance Check","version":"1.0.0"},"servers":[{"url":"https://34.41.139.70:8080"}],"paths":{"/api/v1/compliance/check":{"post":{"summary":"Compliance Check","responses":{"200":{"description":"Success"},"402":{"description":"Payment required"}}}}}}
---

# Compliance Check — $0.010 per call

Validate an x402 settlement against compliance and AML rules.

**Method:** POST
**Path:** /api/v1/compliance/check
**Price:** $0.010 USDC on Solana
**Auth:** Wallet-based (no signup)
**Pay.sh:** `pay skills search api-ep-compliance-check`
