---
category: ai_ml
description: "Translate text with Alibaba Cloud Machine Translation's REST APIs for general-purpose and e-commerce scenarios."
use_case: "Use for synchronous text translation, localization, buyer-seller communication, and e-commerce content workflows that need Alibaba Cloud's classic translation engines."
openapi:
  url: https://production-pay-alibaba-machinetranslation-<RAM>.us-central1.run.app/openapi.json
name: machinetranslation
sandbox_service_url: https://sandbox-pay-alibaba-machinetranslation-<RAM>.us-central1.run.app
service_url: https://production-pay-alibaba-machinetranslation-<RAM>.us-central1.run.app
title: Alibaba Cloud Machine Translation
version: "2019-01-02"

---

## Spend-aware usage

- Set source and target languages explicitly when known instead of spending extra requests on avoidable detection or retries.
- Batch related text into one request when the upstream format allows it instead of paying for many tiny translation calls.
