# Docsumo (docsumo)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
