# PDF.co (pdf-co)

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
