---
name: api-ep-agent-card
title: "Agent Card — NullState"
description: "Generate an A2A Agent Card for your agent with discovery metadata."
use_case: "Generate an A2A Agent Card for your agent with discovery metadata."
category: identity
service_url: https://34.41.139.70:8080
openapi:
  content: |
    {"openapi":"3.1.0","info":{"title":"Agent Card","version":"1.0.0"},"servers":[{"url":"https://34.41.139.70:8080"}],"paths":{"/api/v1/agent/card":{"get":{"summary":"Agent Card","responses":{"200":{"description":"Success"},"402":{"description":"Payment required"}}}}}}
---

# Agent Card — $0.010 per call

Generate an A2A Agent Card for your agent with discovery metadata.

**Method:** GET
**Path:** /api/v1/agent/card
**Price:** $0.010 USDC on Solana
**Auth:** Wallet-based (no signup)
**Pay.sh:** `pay skills search api-ep-agent-card`
