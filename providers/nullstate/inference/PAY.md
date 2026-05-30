---
name: inference
title: "NullState LLM Inference"
description: "Pay-per-call LLM text generation via the Qwen3.6 36B model. $0.005 USDC per request via x402 protocol on Solana. No API key, no signup, no subscription."
use_case: "Use for pay-per-call LLM inference, text generation, code generation, content creation, summarization, and AI task automation without requiring an API key or subscription."
category: ai_ml
service_url: https://greensol.me/nullstate
openapi:
  path: openapi.json
---
Pay-per-call LLM inference via the Qwen3.6 36B model. Each request costs $0.005 USDC,
paid through the x402 protocol on Solana mainnet. No API keys, no signups.

## Spend-aware usage

- Send the shortest prompt that produces the desired output.
- Set max_tokens to the minimum needed for the task.
- Batch related questions into a single prompt when possible.
