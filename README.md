# Docsumo (docsumo)

Docsumo is an intelligent document processing (IDP) platform that uses OCR, computer vision, and machine learning to convert unstructured documents - invoices, bank statements, pay stubs, receipts, tax forms - into structured, validated data. The REST API at https://app.docsumo.com/api/v1 uploads documents, retrieves AI-extracted data, supports human-in-the-loop review, and emits webhooks as documents finish processing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/docsumo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/docsumo/refs/heads/main/apis.yml)

## Tags

- Document Processing
- IDP
- OCR
- Data Extraction
- AI

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Docsumo Documents & Extraction API

Upload documents (multipart file, or URL/Base64), list and summarize documents, fetch document detail, and retrieve AI-extracted structured data and line-item tables for a given document.

- **Human URL:** [https://support.docsumo.com/reference/getting-started-with-your-api](https://support.docsumo.com/reference/getting-started-with-your-api)
- **Base URL:** `https://app.docsumo.com/api/v1`

#### Tags

- Documents
- Upload
- Extraction
- OCR

#### Properties

- [Documentation](https://support.docsumo.com/docs/using-docsumo-api)
- [API Reference](https://support.docsumo.com/reference/getting-started-with-your-api)
- [OpenAPI](openapi/docsumo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/docsumo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/docsumo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Docsumo Document Types API

Lists the document types enabled on the account (invoices, bank statements, pay stubs, receipts, and custom-trained types) and the user/account detail and credit limits used when classifying and routing uploads.

- **Human URL:** [https://support.docsumo.com/docs/document-type-web-api-and-email-limit](https://support.docsumo.com/docs/document-type-web-api-and-email-limit)
- **Base URL:** `https://app.docsumo.com/api/v1`

#### Tags

- Document Types
- Models
- Configuration

#### Properties

- [Documentation](https://support.docsumo.com/docs/using-docsumo-api)
- [API Reference](https://support.docsumo.com/reference/getting-started-with-your-api)
- [OpenAPI](openapi/docsumo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/docsumo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/docsumo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Docsumo Review & Validation API

Generates hosted review URLs for human-in-the-loop validation, updates document review status, and deletes documents once processing and review are complete.

- **Human URL:** [https://support.docsumo.com/reference/getting-started-with-your-api](https://support.docsumo.com/reference/getting-started-with-your-api)
- **Base URL:** `https://app.docsumo.com/api/v1`

#### Tags

- Review
- Validation
- Human in the Loop

#### Properties

- [Documentation](https://support.docsumo.com/docs/using-docsumo-api)
- [API Reference](https://support.docsumo.com/reference/getting-started-with-your-api)
- [OpenAPI](openapi/docsumo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/docsumo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/docsumo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Docsumo Webhooks API

Account-configured webhook callbacks that POST a JSON payload to your endpoint when a document changes processing status (uploaded, processed, reviewed), carrying document identifiers and status for downstream automation.

- **Human URL:** [https://support.docsumo.com/docs/webhook-1](https://support.docsumo.com/docs/webhook-1)
- **Base URL:** `https://app.docsumo.com/api/v1`

#### Tags

- Webhooks
- Events
- Callbacks

#### Properties

- [Documentation](https://support.docsumo.com/docs/webhook-1)
- [Documentation](https://support.docsumo.com/docs/webhook-url-1)
- [Review](review.yml)

## Common Properties

- [GitHub Organization](https://github.com/docsumo)
- [LinkedIn](https://www.linkedin.com/company/docsumo)
- [Website](https://www.docsumo.com)
- [Documentation](https://support.docsumo.com/reference/getting-started-with-your-api)
- [Plans](plans/docsumo-plans-pricing.yml)
- [Rate Limits](rate-limits/docsumo-rate-limits.yml)
- [Fin Ops](finops/docsumo-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
