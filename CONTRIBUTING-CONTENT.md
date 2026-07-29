# Content Strategy

This repository is maintained as a public knowledge base and free online tool directory for label PDF, thermal label printing, barcode label, and ecommerce shipping label workflows.

It is not the AutoShipFlow application source code repository.

## Repository Positioning

Use this repository as a long-term external growth asset:

- Help users understand and fix common label problems.
- Create useful GitHub and Google-indexable troubleshooting pages.
- Link solved problems to relevant AutoShipFlow online tools.
- Collect open-ended real-world cases through GitHub issues.

The tone should be practical, helpful, and problem-first. Avoid writing pages that feel like pure advertising.

## Docs vs Issues

Use `docs/` for problems that already have a stable explanation and a matching tool workflow.

Good docs topics:

- Shipping label prints too small
- Shipping label has too much blank space
- Shipping label prints on two pages
- Resize shipping label PDF to 4x6
- Thermal label paper size mismatch
- Image label to printable PDF
- Scan barcodes from shipping labels
- Extract tracking numbers from label PDFs

Use GitHub issues for open-ended problems where we still need more user cases, file patterns, printer models, or workflow examples.

Good issue topics:

- Collecting cases: print multiple small SKU labels on one 4x6 label
- Collecting cases: label preview looks correct but physical print is shifted
- Collecting cases: printer paper size does not match the PDF
- Collecting cases: label PDFs with CropBox and Rotate metadata
- Collecting cases: auto-rotate labels for printing
- Collecting cases: printer-brand-specific thermal label issues

## Documentation Structure

Use language-prefixed folders:

```text
README.md
README.zh-CN.md
LICENSE
CONTRIBUTING-CONTENT.md
docs/
  en/
    label-printing/
    pdf-label-tools/
    barcode-labels/
    shipping-workflows/
  zh-CN/
    label-printing/
    pdf-label-tools/
    barcode-labels/
    shipping-workflows/
```

Keep file names in English slugs for both languages. This keeps URLs stable and makes the English and Chinese versions easy to pair.

Example:

```text
docs/en/label-printing/label-prints-too-small.md
docs/zh-CN/label-printing/label-prints-too-small.md
```

## Document Template

Each guide should follow this shape:

```md
# Problem title

[Language switch link]

## Problem

Describe what the user sees.

## Common Causes

Explain likely reasons in practical language.

## How to Fix It

Show the recommended AutoShipFlow tool and the basic workflow.

## What the Tool Can and Cannot Fix

Explain the boundary between PDF file layout and printer settings.

## Related Tools

Link to relevant AutoShipFlow tools and related docs.
```

## Issue Template for Open Cases

Open-ended collection issues should invite users to share details without exposing private data.

Suggested structure:

```md
# Collecting cases: topic

## What we are trying to understand

We are collecting real-world cases where...

## Please share

- What label size are you trying to print?
- What paper size is loaded in your printer?
- What tool or platform generated the PDF?
- What does the browser preview show?
- What happens on physical print?
- Printer model, if relevant

Please do not upload files that contain private customer information.
If needed, remove names, addresses, phone numbers, and tracking numbers first.
```

## Content Priority

Start with Label Printing AI because it is the current priority tool and matches strong search intent.

First docs batch:

- `label-prints-too-small.md`
- `resize-shipping-label-to-4x6.md`
- `crop-blank-space-from-label-pdf.md`
- `label-prints-on-two-pages.md`
- `thermal-label-paper-size-mismatch.md`

Then expand gradually:

- PDF Label Resizer
- Crop Label
- Image to PDF Label
- Barcode & QR Scanner
- Extract Tracking Numbers
- Label Renamer / Split Label PDF

## License Boundary

Documentation and public content in this repository use CC BY 4.0.

AutoShipFlow application source code is private and is not included in this repository.
