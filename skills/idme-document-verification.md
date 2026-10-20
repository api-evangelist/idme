---
name: idme-document-verification
description: Verify a driver's license, passport or passport card with the ID.me Services API document endpoints and retrieve the result.
api: ID.me services API
generated: '2026-10-20'
method: generated
source: openapi/_ae-authored/idme-services-openapi-generated.yml
operations:
- post_api_v2_document_license_verify
- post_api_v2_document_passport_verify
- post_api_v2_document_passcard_verify
- get_api_v2_product_transactionId
---
Grounded in a contract GENERATED from docs.id.me (x-generated-from: documentation); confirm fields against https://docs.id.me/apis/services-api/documents.

1. Pick the document type and call `post_api_v2_document_license_verify`, `post_api_v2_document_passport_verify` or `post_api_v2_document_passcard_verify`.
2. Poll `get_api_v2_product_transactionId` with the returned transaction id for the outcome.

Rules: no documented idempotency or reversal; treat each submission as final. Handle 401/403/422/429 per errors/idme-problem-types.yml.
