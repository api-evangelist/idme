---
name: idme-telecom-phone-verification
description: Verify a person's identity and phone possession with the ID.me Services API telecom endpoints (identity match, then SMS one-time code send and confirm).
api: ID.me services API
generated: '2026-10-20'
method: generated
source: openapi/_ae-authored/idme-services-openapi-generated.yml
operations:
- post_api_v2_telecom_identity
- post_api_v2_telecom_possession_sms_send
- post_api_v2_telecom_possession_sms_confirm
- get_api_v2_product_transactionId
---
Grounded in a contract GENERATED from docs.id.me (x-generated-from: documentation); confirm request fields against https://docs.id.me/apis/services-api/telecom before use.

1. `post_api_v2_telecom_identity` — submit the phone and identity attributes; keep the returned transaction id.
2. `post_api_v2_telecom_possession_sms_send` — send a one-time code to the phone.
3. `post_api_v2_telecom_possession_sms_confirm` — confirm the code the user entered.
4. `get_api_v2_product_transactionId` — fetch the transaction result by product and id.

Rules: use the sandbox host (services.idmelabs.com) and the published test personas while testing; no idempotency key is documented, so do not blindly retry POSTs; 429 means rate limited, 422 invalid inputs.
