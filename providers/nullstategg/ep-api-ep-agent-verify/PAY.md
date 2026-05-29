---
name: api-ep-agent-verify
title: "Agent Identity Verify — NullState"
description: "Verify agent identity via KYA challenge-response protocol."
use_case: "Verify agent identity via KYA challenge-response protocol."
category: identity
service_url: https://34.41.139.70:8080
openapi:
  content: |
    {"openapi":"3.1.0","info":{"title":"Agent Identity Verify","version":"1.0.0"},"servers":[{"url":"https://34.41.139.70:8080"}],"paths":{"/api/v1/agent/verify":{"post":{"summary":"Agent Identity Verify","responses":{"200":{"description":"Success"},"402":{"description":"Payment required"}}}}}}
---

# Agent Identity Verify — $0.010 per call

Verify agent identity via KYA challenge-response protocol.

**Method:** POST
**Path:** /api/v1/agent/verify
**Price:** $0.010 USDC on Solana
**Auth:** Wallet-based (no signup)
**Pay.sh:** `pay skills search api-ep-agent-verify`
