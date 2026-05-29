---
name: api-ep-agents-discover
title: "Agent Discovery — NullState"
description: "Discover other AI agents via the ecosystem signals database."
use_case: "Discover other AI agents via the ecosystem signals database."
category: data
service_url: https://34.41.139.70:8080
openapi:
  content: |
    {"openapi":"3.1.0","info":{"title":"Agent Discovery","version":"1.0.0"},"servers":[{"url":"https://34.41.139.70:8080"}],"paths":{"/api/v1/agents/discover":{"get":{"summary":"Agent Discovery","responses":{"200":{"description":"Success"},"402":{"description":"Payment required"}}}}}}
---

# Agent Discovery — $0.010 per call

Discover other AI agents via the ecosystem signals database.

**Method:** GET
**Path:** /api/v1/agents/discover
**Price:** $0.010 USDC on Solana
**Auth:** Wallet-based (no signup)
**Pay.sh:** `pay skills search api-ep-agents-discover`
