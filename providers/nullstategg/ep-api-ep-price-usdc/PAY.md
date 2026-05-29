---
name: api-ep-price-usdc
title: "USDC Price — NullState"
description: "Get current USDC/SOL price feed and market data."
use_case: "Get current USDC/SOL price feed and market data."
category: data
service_url: https://34.41.139.70:8080
openapi:
  content: |
    {"openapi":"3.1.0","info":{"title":"USDC Price","version":"1.0.0"},"servers":[{"url":"https://34.41.139.70:8080"}],"paths":{"/api/v1/price/usdc":{"get":{"summary":"USDC Price","responses":{"200":{"description":"Success"},"402":{"description":"Payment required"}}}}}}
---

# USDC Price — $0.001 per call

Get current USDC/SOL price feed and market data.

**Method:** GET
**Path:** /api/v1/price/usdc
**Price:** $0.001 USDC on Solana
**Auth:** Wallet-based (no signup)
**Pay.sh:** `pay skills search api-ep-price-usdc`
