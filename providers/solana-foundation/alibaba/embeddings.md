---
category: ai_ml
description: "Create text embeddings with Alibaba Cloud Model Studio's OpenAI-compatible embeddings API for retrieval and semantic search."
use_case: "Use for semantic search, retrieval, reranking pipelines, clustering, classification, and vector indexing."
openapi:
  url: https://production-pay-alibaba-embeddings-<RAM>.us-central1.run.app/openapi.json
name: embeddings
sandbox_service_url: https://sandbox-pay-alibaba-embeddings-<RAM>.us-central1.run.app
service_url: https://production-pay-alibaba-embeddings-<RAM>.us-central1.run.app
title: Alibaba Cloud Model Studio Embeddings
version: v1

---

## Spend-aware usage

- Batch related texts into one embeddings request when possible and reuse stored vectors instead of re-embedding unchanged content.
- Only generate embeddings when the task needs retrieval, ranking, clustering, or vector search rather than plain generation.
- Prefer one well-formed request with the right model options over several trial-and-error calls, especially when the body selects the model behavior.
