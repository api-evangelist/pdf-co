# PDF.co (pdf-co)

PDF.co is a PDF and document automation API from Artifex Software, Inc. It exposes a broad surface for AI-driven invoice parsing, template-driven document parsing, bidirectional PDF/Excel/CSV/JSON/XML/HTML/image conversion, OCR, form filling, merging and splitting, barcode generation and recognition, e-signature workflows, PDF compression and optimization, and PDF security. All endpoints share a single base URL (`https://api.pdf.co`), authenticate via the `x-api-key` header, and support both synchronous and asynchronous execution with optional webhook callbacks and `/v1/job/check` polling.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/pdf-co/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - PDF, Document Automation, AI, OCR, Invoice Parsing, Document Parsing, Conversion, Forms, Barcodes, E-Signature

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Authentication

All requests require the `x-api-key` HTTP header. Get a key by signing up at [app.pdf.co/signup](https://app.pdf.co/signup) — the trial includes 10,000 credits for 1 month with no card required.

## Async pattern

Long-running operations (OCR, AI invoice parsing, large file conversion, classification) accept `async: true`. The initial response returns a `jobId`; clients either poll `POST /v1/job/check` or supply a `callback` URL for webhook notification.

## APIs

### PDF.co Extraction API
AI-powered data extraction from PDFs, scans, and images. Includes the zero-template AI Invoice Parser, the template-driven Document Parser (with reusable stored templates), Document Classifier, and PDF attachment extraction.

**Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

- [OpenAPI](openapi/pdf-co-openapi.yml)
- [JSON Schema — AI Invoice Parser Request](json-schema/pdf-co-ai-invoice-parser-schema.json)
- [JSON Schema — Document Parser Request](json-schema/pdf-co-document-parser-schema.json)
- [JSON-LD](json-ld/pdf-co-context.jsonld)
- [Naftiko Capability — Extraction](capabilities/extraction.yaml)
- [Example — AI Invoice Parser](examples/pdf-co-ai-invoice-parser-example.json)

### PDF.co Conversion API
Bidirectional conversion: PDF to CSV/JSON/JSON-AI/text/XML/XLS/XLSX/HTML/JPG/PNG/TIFF/WebP; PDF from HTML, URL, DOC/DOCX, CSV/XLS/XLSX, images, and email (.msg, .eml); plus Excel-to-anything.

**Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

- [OpenAPI](openapi/pdf-co-openapi.yml)
- [Naftiko Capability — Conversion](capabilities/conversion.yaml)
- [Example — PDF to JSON](examples/pdf-co-pdf-to-json-example.json)

### PDF.co Editing API
Programmatic editing: add text/images/forms/links, search-and-replace, replace text with images, delete text.

**Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

- [OpenAPI](openapi/pdf-co-openapi.yml)
- [Naftiko Capability — Editing](capabilities/editing.yaml)

### PDF.co Merging and Splitting API
Merge multiple PDFs (or mixed PDF/DOC/XLS/image inputs via `/merge2`); split by page ranges, indexes, or text pattern.

**Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

- [OpenAPI](openapi/pdf-co-openapi.yml)
- [Naftiko Capability — Merging and Splitting](capabilities/merging-splitting.yaml)

### PDF.co Find and Search API
Locate text and tables with coordinates; OCR-driven `/makesearchable`; remove text layer via `/makeunsearchable`.

**Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

- [OpenAPI](openapi/pdf-co-openapi.yml)
- [Naftiko Capability — Find and Search](capabilities/find-search.yaml)

### PDF.co Forms API
Read fillable form field metadata (AcroForm, XFA). Pair with the Editing API to fill forms programmatically.

**Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

- [OpenAPI](openapi/pdf-co-openapi.yml)
- [Naftiko Capability — Forms](capabilities/forms.yaml)

### PDF.co Pages API
Delete or rotate pages; AI-driven auto-rotation for scanned documents.

**Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

- [OpenAPI](openapi/pdf-co-openapi.yml)
- [Naftiko Capability — Pages](capabilities/pages.yaml)

### PDF.co Barcodes API
Generate barcodes (QR, Code128, DataMatrix, PDF417, EAN, UPC, and more) and read barcodes from PDF/image URLs.

**Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

- [OpenAPI](openapi/pdf-co-openapi.yml)
- [Naftiko Capability — Barcodes](capabilities/barcodes.yaml)

### PDF.co Document, File, and System API
Platform primitives: file upload (form, base64, URL, presigned), download, delete, MD5 hash; PDF compress (v2) and optimize; PDF info; classifier; email decode/send/extract-attachments; HTML templates store; `/v1/job/check` for async polling; `/v1/account/credit/balance`.

**Human URL:** [https://docs.pdf.co/api-reference](https://docs.pdf.co/api-reference)

- [OpenAPI](openapi/pdf-co-openapi.yml)
- [Naftiko Capability — Document, File, and System](capabilities/document-file-system.yaml)

## Plans, rate limits, and FinOps

- [Plans and pricing](plans/pdf-co-plans-pricing.yml) — Free trial (10,000 credits/mo for 1 month), Basic ($8.99 / 16,500 cr), Personal ($22.49 / 37,000 cr), Business 1 ($44.99 / 80,500 cr), Business 2 ($89.99 / 159,850 cr), Business 3 ($270 / 483,000 cr), Enterprise (custom).
- [Rate limits and quotas](rate-limits/pdf-co-rate-limits.yml) — Credit-based monthly quota; concurrency scales with plan; async-first for heavy ops.
- [FinOps profile](finops/pdf-co-finops.yml) — FOCUS-aligned meters: credits consumed, credits remaining, API calls, pages processed, async job count.

## SDKs and tooling

- [API code samples (multi-language)](https://github.com/pdfdotco/pdf-co-api-samples) — JavaScript, C#, VB.NET, Java, PHP, Python, Go, Bash
- [PDF.co MCP server](https://github.com/pdfdotco/pdfco-mcp) — Model Context Protocol server (Python, MIT)
- [PDF.co n8n node](https://github.com/pdfdotco/n8n-nodes-pdfco) — TypeScript, MIT
- [3,000+ integrations](https://pdf.co/integrations) — Zapier, Make, n8n, and more

## Common links

- [Home](https://pdf.co) / [Docs](https://docs.pdf.co) / [API Reference](https://docs.pdf.co/api-reference) / [OpenAPI JSON](https://docs.pdf.co/openapi.json)
- [Sign up](https://app.pdf.co/signup) / [Dashboard](https://app.pdf.co/account/dashboard)
- [Pricing](https://pdf.co/pricing) / [Support](https://support.pdf.co/en) / [Blog](https://pdf.co/resources/blog) / [Tutorials](https://pdf.co/tutorials)
- [GitHub org](https://github.com/pdfdotco) / [Security (SOC 2)](https://docs.pdf.co/knowledgebase/security)
- [Webhooks & Callbacks glossary](https://docs.pdf.co/glossary/webhook-and-callbacks)
