---
name: nullstate-gateway
title: "NullState x402 Settlement Gateway"
description: "Open-source x402 settlement verification for AI agents on Solana. Verify on-chain USDC settlements and manage credit pools."
use_case: "Use for x402 settlement verification — verify USDC transfers to your wallet on Solana. Post a tx hash and get a verified receipt."
category: developer-tools
service_url: https://34.41.139.70:8080
openapi:
  path: openapi.json
---

NullState is an open-source settlement gateway for the x402 agent economy.  
Agents verify USDC payments on Solana by submitting transaction hashes.

## Endpoints

### POST /api/settlement/verify
Verify a Solana USDC settlement. Accepts a transaction hash, checks the Solana mainnet for a USDC transfer to the NullState wallet.

**Request:**
```json
{"hash": "<solana_tx_signature>", "asset": "USDC", "network": "Solana", "amount": 4.99}
```

**Response (verified):**
```json
{"success": true, "tx_id": "abc123", "amount": 4.99, "asset": "USDC", "network": "Solana", "settled_to": "2d2YcoLKSbEBY2sUR76Pfp9QifdsQQpRWYXU2TfVsALX"}
```

### GET /health
Gateway and ledger status.

### GET /.well-known/agent-card.json
A2A Agent Card for autonomous discovery.

## Spend-aware usage

- Submit only confirmed Solana mainnet transaction signatures (64-char base58)
- Amount check is inclusive — amounts equal or greater than requested pass
- No SOL needed for verification (read-only RPC check)
- Credits are auto-deposited on successful verification

## Pricing

| Tier | Price | Requests/Month |
|------|-------|----------------|
| Free | $0    | 5              |
| Scout | $50  | 500            |
| Pro  | $200  | 5,000          |
| Enterprise | $500 | Unlimited |

All prices in USDC on Solana.
