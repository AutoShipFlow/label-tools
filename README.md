# Label Tools

[简体中文](./README.zh-CN.md)

A public knowledge base and free online tool directory for shipping label PDFs, thermal label printing issues, barcode labels, and ecommerce label workflows.

This repository contains public documentation, troubleshooting guides, and links to AutoShipFlow online tools. It does not include the AutoShipFlow application source code.

## Choose a Label Problem

Start from the problem you see, then either read the troubleshooting guide or open the matching online tool.

### Printing Size and Paper Mismatch

For labels that print too small, too large, with extra blank space, across two pages, or on the wrong thermal label paper.

- **Shipping label prints too small**: crop blank space and fit the label to the real paper size. [📖 Guide](./docs/en/label-printing/label-prints-too-small.md) · [🚀 Try](https://www.autoshipflow.com/tools/label-printing-ai)
- **Resize shipping label PDF to 4x6**: prepare carrier labels for common 4 x 6 in thermal label printers. [📖 Guide](./docs/en/label-printing/resize-shipping-label-to-4x6.md) · [🚀 Try](https://www.autoshipflow.com/tools/label-printing-ai)
- **Crop blank space from a label PDF**: remove large margins that make the printed label look tiny. [📖 Guide](./docs/en/label-printing/crop-blank-space-from-label-pdf.md) · [🚀 Try](https://www.autoshipflow.com/tools/crop-label)
- **Shipping label prints on two pages**: fit one complete label onto one selected label page. [📖 Guide](./docs/en/label-printing/label-prints-on-two-pages.md) · [🚀 Try](https://www.autoshipflow.com/tools/label-printing-ai)
- **Thermal label paper size mismatch**: separate PDF layout issues from printer paper, scale, margin, or driver settings. [📖 Guide](./docs/en/label-printing/thermal-label-paper-size-mismatch.md) · [🚀 Try](https://www.autoshipflow.com/tools/label-printing-ai)

### PDF Label Preparation

For preparing label files before printing, sharing, or batch processing.

- **Resize PDF label pages**: change label PDF page size for 4x6, 4x4, 100 x 150 mm, or custom label paper. [🚀 Try](https://www.autoshipflow.com/tools/pdf-resize)
- **Crop PDF label content**: remove blank space or crop to a specific label area. [🚀 Try](https://www.autoshipflow.com/tools/crop-label)
- **Convert label images to PDF**: turn PNG, JPG, or WebP label images into printable label PDFs. [🚀 Try](https://www.autoshipflow.com/tools/image-to-pdf-label)

### Barcode and QR Labels

For reading barcode data from shipping labels, product labels, and warehouse labels.

- **Scan barcodes and QR codes from shipping labels**: read Code 128, QR, Data Matrix, PDF417, and other label codes from PDFs or images. [🚀 Try](https://www.autoshipflow.com/tools/barcode-scan)

### Tracking Number Workflows

For organizing batches of shipping labels by tracking number.

- **Extract tracking numbers from label PDFs or images**: copy tracking numbers from shipping labels without manually reading each file. [🚀 Try](https://www.autoshipflow.com/tools/extract-tracking-numbers)

## Free Online Tools

- [Label Printing AI](https://www.autoshipflow.com/tools/label-printing-ai)
- [PDF Label Resizer](https://www.autoshipflow.com/tools/pdf-resize)
- [Crop Label](https://www.autoshipflow.com/tools/crop-label)
- [Image to PDF Label](https://www.autoshipflow.com/tools/image-to-pdf-label)
- [Barcode & QR Scanner](https://www.autoshipflow.com/tools/barcode-scan)
- [Extract Tracking Numbers](https://www.autoshipflow.com/tools/extract-tracking-numbers)

## How to Use This Repository

Use this repository as a troubleshooting map:

1. Find the label problem that matches what you see.
2. Read the guide to understand common causes and printer-setting boundaries.
3. Open the matching AutoShipFlow tool to process the PDF or image.
4. Preview the result, then print with the correct paper size and 100% / Actual size scale.

## Content Strategy

See [Content Strategy](./CONTRIBUTING-CONTENT.md) for how this repository separates stable troubleshooting guides from open-ended GitHub issue collection topics.

## Important Boundary

AutoShipFlow online tools can adjust PDF pages, crop blank space, resize labels, merge files, and generate printable PDFs. They cannot read or change the actual paper loaded in your printer.

If the processed PDF preview looks correct but the physical print is shifted, scaled incorrectly, or cut off, check your printer paper size, scale, margins, calibration, and driver settings.

## License

The documentation and content in this repository are licensed under the [Creative Commons Attribution 4.0 International License](./LICENSE) (CC BY 4.0).

AutoShipFlow application source code is not included in this repository.
