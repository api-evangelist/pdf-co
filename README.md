# PDF.co (pdf-co)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pdf-co/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pdf-co/refs/heads/main/apis.yml)

## Scope

- **Access:** 3rd-Party

## Tags

- PDF
- Document Automation
- AI
- OCR
- Invoice Parsing
- Document Parsing
- Conversion
- Forms
- Barcodes
- E-Signature

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### PDF.co Extraction API

AI-powered data extraction from PDF, scanned, and image-based documents. Includes the AI Invoice Parser (zero-template invoice/receipt parsing), Document Parser (template-driven extraction with reusable templates by ID), Document Classifier, and PDF attachment extraction. Async and sync modes; webhook callbacks; supports URL, base64, or uploaded-file inputs.

- **Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

#### Tags

- AI
- Document Parsing
- Invoice Parsing
- OCR
- Extraction

#### Properties

- [Documentation](https://docs.pdf.co/api-reference)
- [OpenAPI](openapi/pdf-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pdf-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pdf-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/pdf-co-document-parser-schema.json) — [JSON Schema](https://json-schema.org/specification)

### PDF.co Conversion API

Bidirectional document conversion: PDF to CSV, JSON, JSON-AI, text, XML, XLS, XLSX, HTML, JPG, PNG, TIFF, WebP; PDF from HTML, URL, DOC/DOCX, CSV/XLS/XLSX, images, and email (.msg, .eml); plus Excel-to-anything conversion. Layout-preserving table extraction and AI-driven JSON output supported.

- **Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

#### Tags

- Conversion
- PDF
- Excel
- CSV
- JSON
- HTML
- Images
- OCR

#### Properties

- [Documentation](https://docs.pdf.co/api-reference)
- [OpenAPI](openapi/pdf-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pdf-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pdf-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PDF.co Editing API

Programmatic PDF editing: add text/images/forms/links, replace text, replace text with images, delete text, delete or rotate pages, AI auto-rotate, search-and-replace, and form filling. Accepts coordinate-based annotations and supports template-driven PDF generation via HTML templates.

- **Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

#### Tags

- Editing
- PDF
- Forms
- Text
- Images

#### Properties

- [Documentation](https://docs.pdf.co/api-reference)
- [OpenAPI](openapi/pdf-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pdf-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pdf-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PDF.co Merging and Splitting API

Merge multiple PDFs (and DOC, XLS, image inputs via /merge2) into a single document, or split PDFs by page ranges, indexes, or text-pattern search. Useful for document assembly, statement bursting, and invoice pipelines.

- **Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

#### Tags

- Merging
- Splitting
- PDF
- Document Assembly

#### Properties

- [Documentation](https://docs.pdf.co/api-reference)
- [OpenAPI](openapi/pdf-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pdf-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pdf-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PDF.co Find and Search API

Locate text in PDFs and return coordinates (`/pdf/find`), AI-powered table location (`/pdf/find/table`), and make scanned PDFs text-searchable via OCR (`/pdf/makesearchable`) or remove text layers to produce image-only PDFs (`/pdf/makeunsearchable`).

- **Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

#### Tags

- Search
- PDF
- OCR
- Text

#### Properties

- [Documentation](https://docs.pdf.co/api-reference)
- [OpenAPI](openapi/pdf-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pdf-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pdf-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PDF.co Forms API

Retrieve fillable form field details (`/pdf/info/fields`) for AcroForm and XFA PDFs. Pair with the Editing API's `/pdf/edit/add` endpoint to fill forms programmatically.

- **Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

#### Tags

- Forms
- PDF
- AcroForm

#### Properties

- [Documentation](https://docs.pdf.co/api-reference)
- [OpenAPI](openapi/pdf-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pdf-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pdf-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PDF.co Pages API

Delete pages by range, rotate pages by degrees, or use AI auto-rotation to detect and fix page orientation in scanned documents.

- **Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

#### Tags

- Pages
- PDF
- Rotation

#### Properties

- [Documentation](https://docs.pdf.co/api-reference)
- [OpenAPI](openapi/pdf-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pdf-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pdf-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PDF.co Barcodes API

Generate high-quality barcode images (QR, Code128, DataMatrix, PDF417, EAN, UPC, and others) or read barcodes from PDF and image inputs by URL.

- **Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

#### Tags

- Barcodes
- QR Code
- Recognition

#### Properties

- [Documentation](https://docs.pdf.co/api-reference)
- [OpenAPI](openapi/pdf-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pdf-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pdf-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PDF.co Document, File, and System API

File operations and platform primitives: upload (form, base64, by URL, presigned URL), download, delete, MD5 hash; PDF compress (v2) and optimize; PDF info reader; email decode/send/extract-attachments; HTML template storage; document classifier; and the `/job/check` endpoint for polling async operations. Also exposes `/account/credit/balance` for credit reporting.

- **Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

#### Tags

- Files
- Compression
- Optimization
- Email
- Templates
- Jobs
- Account

#### Properties

- [Documentation](https://docs.pdf.co/api-reference)
- [OpenAPI](openapi/pdf-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pdf-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pdf-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://pdf.co)
- [Documentation](https://docs.pdf.co)
- [Documentation](https://docs.pdf.co/api-reference)
- [OpenAPI](https://docs.pdf.co/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Sign Up](https://app.pdf.co/signup)
- [Login](https://app.pdf.co/account/dashboard)
- [Pricing](https://pdf.co/pricing)
- [Support](https://support.pdf.co/en)
- [Documentation](https://pdf.co/integrations)
- [Git Hub](https://github.com/pdfdotco)
- [Source Code](https://github.com/pdfdotco/pdf-co-api-samples)
- [M C P](https://github.com/pdfdotco/pdfco-mcp)
- [Plugin](https://github.com/pdfdotco/n8n-nodes-pdfco)
- [Blog](https://pdf.co/resources/blog)
- [Documentation](https://pdf.co/tutorials)
- [Security](https://docs.pdf.co/knowledgebase/security)
- [Terms of Service](https://pdf.co/terms)
- [Privacy](https://pdf.co/privacy)
- [Authentication](https://docs.pdf.co/api-reference/authentication)
- [Webhooks](https://docs.pdf.co/glossary/webhook-and-callbacks)
- [About](https://pdf.co/about)
- [Plans](plans/pdf-co-plans-pricing.yml)
- [Rate Limits](rate-limits/pdf-co-rate-limits.yml)
- [Fin Ops](finops/pdf-co-finops.yml)
