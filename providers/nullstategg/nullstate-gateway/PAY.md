---
name: nullstate-gateway
title: "NullState Gateway — 15 Paid Endpoints"
description: "Open-source x402 gateway with 15 paid endpoints for settlement, credits, identity, and data."
use_case: "Use for x402 settlement verification, credit management, agent identity, wallet balance checks, and Solana network data. All endpoints pay-per-call with USDC on Solana."
category: payments
service_url: https://34.41.139.70:8080
openapi:
  path: openapi.json
---

# NullState Multi-Tenant Payment Gateway

Open-source x402 gateway network with 15 paid endpoints for the agent economy.

## Endpoints

| Endpoint | Method | Price | Category |
|----------|--------|-------|----------|
| `/api/v1/settlement/verify` | POST | $0.010 | payments |
| `/api/v1/credits/balance` | GET | $0.005 | payments |
| `/api/v1/settlement/receipt` | POST | $0.010 | payments |
| `/api/v1/agent/verify` | POST | $0.010 | identity |
| `/api/v1/wallet/balance` | GET | $0.001 | data |
| `/api/v1/transaction/history` | GET | $0.005 | data |
| `/api/v1/compliance/check` | POST | $0.010 | identity |
| `/api/v1/proof/generate` | POST | $0.020 | payments |
| `/api/v1/price/usdc` | GET | $0.001 | data |
| `/api/v1/ledger/summary` | GET | $0.005 | data |
| `/api/v1/agent/card` | GET | $0.010 | identity |
| `/api/v1/webhook/verify` | POST | $0.005 | developer-tools |
| `/api/v1/network/status` | GET | $0.001 | data |
| `/api/v1/agents/discover` | GET | $0.010 | data |
| `/api/v1/billing/estimate` | POST | $0.005 | payments |

## Spend-aware usage

- All prices in USDC on Solana mainnet
- No API key or account required — wallet is identity
- Submit confirmed Solana tx signatures only (64-char base58)
- Credits auto-deposited on successful verification
- Card payments accepted on select endpoints (Visa/MC via Stripe)

## Agent Discovery

Agents discover NullState endpoints via:
- Pay.sh registry (`pay skills search nullstate`)
- A2A Agent Card at `/.well-known/agent-card.json`
- x402list.fun directory

## Pricing Summary

| `/api/v1/settlement/verify` | POST | $0.010 | Verify a Solana USDC settlement transaction. Submit tx hash, get verified receipt with on-chain proof. |
| `/api/v1/credits/balance` | GET | $0.005 | Check prepaid USDC credit balance for any agent wallet. |
| `/api/v1/settlement/receipt` | POST | $0.010 | Generate a signed settlement receipt for audit trails and dispute resolution. |
| `/api/v1/agent/verify` | POST | $0.010 | Verify agent identity via KYA challenge-response protocol. |
| `/api/v1/wallet/balance` | GET | $0.001 | Check on-chain USDC/SOL balance of any Solana wallet address. |
| `/api/v1/transaction/history` | GET | $0.005 | Get settlement transaction history for any agent. |
| `/api/v1/compliance/check` | POST | $0.010 | Validate an x402 settlement against compliance and AML rules. |
| `/api/v1/proof/generate` | POST | $0.020 | Generate cryptographic proof of settlement for dispute resolution. |
| `/api/v1/price/usdc` | GET | $0.001 | Get current USDC/SOL price feed and market data. |
| `/api/v1/ledger/summary` | GET | $0.005 | Get a summary of all ledger activity and balances. |
| `/api/v1/agent/card` | GET | $0.010 | Generate an A2A Agent Card for your agent with discovery metadata. |
| `/api/v1/webhook/verify` | POST | $0.005 | Verify webhook payload signatures. |
| `/api/v1/network/status` | GET | $0.001 | Check Solana network health and latest confirmed slot. |
| `/api/v1/agents/discover` | GET | $0.010 | Discover other AI agents via the ecosystem signals database. |
| `/api/v1/billing/estimate` | POST | $0.005 | Estimate billing costs for a given usage pattern. |
