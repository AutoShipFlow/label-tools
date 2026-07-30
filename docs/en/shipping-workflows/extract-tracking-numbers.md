# Extract Tracking Numbers from Label PDFs or Images

[简体中文](../../../zh-CN/shipping-workflows/extract-tracking-numbers.md)

## Problem

You have a batch of shipping labels and need to copy tracking numbers into an ERP, WMS, spreadsheet, customer service system, or carrier tracking page. Reading each label manually is slow and error-prone.

## Common Causes

- Shipping labels are exported as PDF or image files instead of structured data.
- Tracking numbers are encoded in barcodes, but the visible text can be small or blurry.
- A batch may include USPS, UPS, FedEx, DHL, Amazon, or other carrier labels.
- Manual copy and paste easily introduces missing digits or wrong labels.

## How to Fix It

Use [Extract Tracking Numbers](https://www.autoshipflow.com/tools/extract-tracking-numbers):

1. Upload PDF or image labels.
2. Scan the labels in your browser.
3. Review the recommended tracking numbers.
4. Copy the results or download a CSV for your workflow.

## What the Tool Can and Cannot Fix

The tool can scan barcodes and identify likely tracking numbers from label files.

It cannot guarantee that every barcode on a label is the main tracking number. Some labels include order barcodes, warehouse barcodes, return codes, or carrier routing codes. Review the results before using them for bulk operations.

## Related Tools

- [Extract Tracking Numbers](https://www.autoshipflow.com/tools/extract-tracking-numbers)
- [Barcode & QR Scanner](https://www.autoshipflow.com/tools/barcode-scan)
- [Label Renamer](https://www.autoshipflow.com/tools/label-renamer)
