---
category: ai_ml
description: "Extract contract fields, generate review results, and answer legal questions with Alibaba Cloud FaRui."
use_case: "Use for contract Extraction, generate contract review result, legal Consultation, and related contract review, legal extraction, compliance checks, and legal advisory workflows."
openapi:
  url: https://production-pay-alibaba-farui-<RAM>.us-central1.run.app/openapi.json
name: farui
sandbox_service_url: https://sandbox-pay-alibaba-farui-<RAM>.us-central1.run.app
service_url: https://production-pay-alibaba-farui-<RAM>.us-central1.run.app
title: Alibaba Cloud FaRui
version: "2024-06-28"

---

## Spend-aware usage

- Use the narrowest legal endpoint for the task, such as extraction, review-result generation, or consultation, and provide the needed contract context up front.
- Do not pay for full legal-analysis flows when a smaller field-extraction or clause-specific result is enough.
- This provider exposes only the allowlisted stateless synchronous subset from the paired gateway manifest. Do not assume async jobs or stateful resource-management APIs are available unless the spec shows them explicitly.
